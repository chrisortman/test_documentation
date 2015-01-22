1. Get the unique database ID of the provider, program, or core to be removed.  This can be either acquired via the rails console or directly from the database
2. Start a rails console `rails c`
3. Grab the provider, program, or core 
`org = Organization.find <insert unique ID>`
4. Gather the unique database IDs for all services under the desired provider, program, or core 
`service_ids = org.all_child_services.map(&:id)`
5. Check whether line items exist with those service ids 
`LineItem.where(:service_id => service_ids).count`
6. If the above count returns zero (0) you can safely remove the provider, program, or core.
7. In order to delete all data below you would need to loop over child organizations and delete them first.  
Example if trying to delete a provider.  `org.programs.each{|program| program.cores.each(&:destroy); program.destroy; org.destroy}`
8. If the count in step 5 is greater than zero additional steps would be required.  This can be as simple as moving the services to a new/existing organization or very complex which would include determining statuses of service requests and removing line items. 
