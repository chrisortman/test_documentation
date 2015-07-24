    # Logfile created on 2013-10-25 16:13:41 -0400 by logger.rb/31641
    SOAP request: https://interconnect.musc.edu/Interconnect-SPARC-PRD/Wcf/Epic.EDI.IHEWcf.Services/ProtocolExecutor.svc
    SOAPAction: "RetrieveProtocolDefResponse", Content-Type: application/soap+xml;charset=UTF-8, Content-Length: 66860
    <?xml version="1.0" encoding="UTF-8"?>
    <env:Envelope xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns="urn:ihe:qrph:rpe:2009" xmlns:env="http://www.w3.org/2003/05/soap-envelope" xmlns:wsa="http://www.w3.org/2005/08/addressing">
      <env:Header>
        <wsa:Action>urn:ihe:qrph:rpe:2009:RetrieveProtocolDefResponse</wsa:Action>
        <wsa:MessageID>uuid:7ae8dd80-7e33-4c9f-b99e-4c716c46d6a2</wsa:MessageID>
        <wsa:To>https://interconnect.musc.edu/Interconnect-SPARC-PRD/Wcf/Epic.EDI.IHEWcf.Services/ProtocolExecutor.svc</wsa:To>
      </env:Header>
      <env:Body>
        <RetrieveProtocolDefResponse><query root="1.2.5.2.3.4" extension="101282"/>
    <protocolDef>
      <plannedStudy xmlns="urn:hl7-org:v3" classCode="CLNTRL" moodCode="DEF">
        <id root="1.2.5.2.3.4" extension="101282"/>
        <title>A Randomized Open-Label Multi-Institution Phase II Study of the Combination of Bevacizumab and Erlotinib Compared to Sorafenib in the First-Line Treatment of Patients with Advanced Hepatocellular Carcinoma (HCC)</title>
        <text/>
        <subjectOf typeCode="SUBJ">
          <studyCharacteristic classCode="OBS" moodCode="EVN">
            <code code="SC"/>
            <value xsi:type="CD" code="THOMASTR" codeSystem="netid"/>
          </studyCharacteristic>
        </subjectOf>
        <subjectOf typeCode="SUBJ">
          <studyCharacteristic classCode="OBS" moodCode="EVN">
            <code code="SC"/>
            <value xsi:type="CD" code="HARRISLO" codeSystem="netid"/>
          </studyCharacteristic>
        </subjectOf>
        <subjectOf typeCode="SUBJ">
          <studyCharacteristic classCode="OBS" moodCode="EVN">
            <code code="SC"/>
            <value xsi:type="CD" code="ARA20" codeSystem="netid"/>
          </studyCharacteristic>
        </subjectOf>
        <subjectOf typeCode="SUBJ">
          <studyCharacteristic classCode="OBS" moodCode="EVN">
            <code code="SC"/>
            <value xsi:type="CD" code="MACKB" codeSystem="netid"/>
          </studyCharacteristic>
        </subjectOf>
        <subjectOf typeCode="SUBJ">
          <studyCharacteristic classCode="OBS" moodCode="EVN">
            <code code="SC"/>
            <value xsi:type="CD" code="JMD29" codeSystem="netid"/>
          </studyCharacteristic>
        </subjectOf>
        <subjectOf typeCode="SUBJ">
          <studyCharacteristic classCode="OBS" moodCode="EVN">
            <code code="SC"/>
            <value xsi:type="CD" code="MIZELLK" codeSystem="netid"/>
          </studyCharacteristic>
        </subjectOf>
        <subjectOf typeCode="SUBJ">
          <studyCharacteristic classCode="OBS" moodCode="EVN">
            <code code="SC"/>
            <value xsi:type="CD" code="BRISEND" codeSystem="netid"/>
          </studyCharacteristic>
        </subjectOf>
        <subjectOf typeCode="SUBJ">
          <studyCharacteristic classCode="OBS" moodCode="EVN">
            <code code="SC"/>
            <value xsi:type="CD" code="SHANNSU" codeSystem="netid"/>
          </studyCharacteristic>
        </subjectOf>
        <subjectOf typeCode="SUBJ">
          <studyCharacteristic classCode="OBS" moodCode="EVN">
            <code code="PI"/>
            <value xsi:type="CD" code="MBT2" codeSystem="netid"/>
          </studyCharacteristic>
        </subjectOf>
        <subjectOf typeCode="SUBJ">
          <studyCharacteristic classCode="OBS" moodCode="EVN">
            <code code="SC"/>
            <value xsi:type="CD" code="TDS7" codeSystem="netid"/>
          </studyCharacteristic>
        </subjectOf>
        <subjectOf typeCode="SUBJ">
          <studyCharacteristic classCode="OBS" moodCode="EVN">
            <code code="SC"/>
            <value xsi:type="CD" code="OREARDS" codeSystem="netid"/>
          </studyCharacteristic>
        </subjectOf>
        <subjectOf typeCode="SUBJ">
          <studyCharacteristic classCode="OBS" moodCode="EVN">
            <code code="SC"/>
            <value xsi:type="CD" code="CLH44" codeSystem="netid"/>
          </studyCharacteristic>
        </subjectOf>
        <subjectOf typeCode="SUBJ">
          <studyCharacteristic classCode="OBS" moodCode="EVN">
            <code code="SC"/>
            <value xsi:type="CD" code="MATSONT" codeSystem="netid"/>
          </studyCharacteristic>
        </subjectOf>
        <subjectOf typeCode="SUBJ">
          <studyCharacteristic classCode="OBS" moodCode="EVN">
            <code code="IRB"/>
            <value xsi:type="ST" value="18832"/>
          </studyCharacteristic>
        </subjectOf>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574"/>
            <title>Sorafenib</title>
            <code code="CELL" codeSystem="n/a"/>
            <component1 typeCode="COMP">
              <sequenceNumber value="1"/>
              <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1"/>
                <title>Cycle 1</title>
                <code code="CYCLE" codeSystem="n/a"/>
                <effectiveTime>
                  <low value="20090321"/>
                  <high value="20090321"/>
                </effectiveTime>
                <component1 typeCode="COMP">
                  <sequenceNumber value="1"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY1"/>
                    <title>Screening</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="2"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY2"/>
                    <title>C1 D1</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="3"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY3"/>
                    <title>C1 D8</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="4"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY4"/>
                    <title>C1 D15</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="5"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY5"/>
                    <title>C1 D22</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="6"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY6"/>
                    <title>C2 D1</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="7"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY7"/>
                    <title>C2 D15</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="8"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY8"/>
                    <title>C3 D1</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="9"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY9"/>
                    <title>C4 D1</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="10"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY10"/>
                    <title>C5 D1</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="11"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY11"/>
                    <title>C6D1</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="12"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY12"/>
                    <title>C7 D1</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="13"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY13"/>
                    <title>C8 D1</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="14"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY14"/>
                    <title>C0 D1</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="15"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY15"/>
                    <title>C10 D1</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="16"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY16"/>
                    <title>EOT</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="17"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY17"/>
                    <title>Additional</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="18"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY18"/>
                    <title>Visit 18</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="19"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY19"/>
                    <title>Visit 19</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="20"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY20"/>
                    <title>Visit 20</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="21"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY21"/>
                    <title>Visit 21</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="22"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY22"/>
                    <title>Visit 22</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="23"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY23"/>
                    <title>Visit 23</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="24"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY24"/>
                    <title>Visit 24</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="25"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY25"/>
                    <title>Visit 25</title>
                  </timePointEventDefinition>
                </component1>
              </timePointEventDefinition>
            </component1>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575"/>
            <title>Bevacizumab + Erlonitib</title>
            <code code="CELL" codeSystem="n/a"/>
            <component1 typeCode="COMP">
              <sequenceNumber value="2"/>
              <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1"/>
                <title>Cycle 1</title>
                <code code="CYCLE" codeSystem="n/a"/>
                <effectiveTime>
                  <low value="20090321"/>
                  <high value="20090321"/>
                </effectiveTime>
                <component1 typeCode="COMP">
                  <sequenceNumber value="1"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY1"/>
                    <title>Screening</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="2"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY2"/>
                    <title>C1 D1</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="3"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY3"/>
                    <title>C1 D8</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="4"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY4"/>
                    <title>C1 D15</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="5"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY5"/>
                    <title>C1 D22</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="6"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY6"/>
                    <title>C2 D1</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="7"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY7"/>
                    <title>C2 D15</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="8"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY8"/>
                    <title>C3 D1</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="9"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY9"/>
                    <title>C4 D1</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="10"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY10"/>
                    <title>C5 D1</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="11"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY11"/>
                    <title>C6 D1</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="12"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY12"/>
                    <title>C7 D1</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="13"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY13"/>
                    <title>C8 D1</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="14"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY14"/>
                    <title>C9 D1</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="15"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY15"/>
                    <title>C10 D1</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="16"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY16"/>
                    <title>EOT</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="17"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY17"/>
                    <title>Visit 17</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="18"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY18"/>
                    <title>Visit 18</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="19"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY19"/>
                    <title>Visit 19</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="20"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY20"/>
                    <title>Visit 20</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="21"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY21"/>
                    <title>Visit 21</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="22"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY22"/>
                    <title>Visit 22</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="23"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY23"/>
                    <title>Visit 23</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="24"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY24"/>
                    <title>Visit 24</title>
                  </timePointEventDefinition>
                </component1>
                <component1 typeCode="COMP">
                  <sequenceNumber value="25"/>
                  <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                    <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY25"/>
                    <title>Visit 25</title>
                  </timePointEventDefinition>
                </component1>
              </timePointEventDefinition>
            </component1>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY1"/>
            <title>Screening</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component1 typeCode="COMP">
              <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY1.PROC11605"/>
                <code code="PROC" codeSystem="CPT"/>
                <component2 typeCode="COMP">
                  <procedure classCode="PROC" moodCode="EVN">
                    <code code="93000" codeSystem="CPT"/>
                  </procedure>
                </component2>
              </timePointEventDefinition>
            </component1>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY2"/>
            <title>C1 D1</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component1 typeCode="COMP">
              <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY2.PROC11606"/>
                <code code="PROC" codeSystem="CPT"/>
                <component2 typeCode="COMP">
                  <procedure classCode="PROC" moodCode="EVN">
                    <code code="80053" codeSystem="CPT"/>
                  </procedure>
                </component2>
                <subjectOf>
                  <timePointEventCharacteristic>
                    <code code="BILL_MODIFIER" codeSystem="n/a"/>
                    <value value="Q1"/>
                  </timePointEventCharacteristic>
                </subjectOf>
              </timePointEventDefinition>
            </component1>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY3"/>
            <title>C1 D8</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY4"/>
            <title>C1 D15</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component1 typeCode="COMP">
              <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY4.PROC11606"/>
                <code code="PROC" codeSystem="CPT"/>
                <component2 typeCode="COMP">
                  <procedure classCode="PROC" moodCode="EVN">
                    <code code="80053" codeSystem="CPT"/>
                  </procedure>
                </component2>
                <subjectOf>
                  <timePointEventCharacteristic>
                    <code code="BILL_MODIFIER" codeSystem="n/a"/>
                    <value value="Q1"/>
                  </timePointEventCharacteristic>
                </subjectOf>
              </timePointEventDefinition>
            </component1>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY5"/>
            <title>C1 D22</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY6"/>
            <title>C2 D1</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component1 typeCode="COMP">
              <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY6.PROC11606"/>
                <code code="PROC" codeSystem="CPT"/>
                <component2 typeCode="COMP">
                  <procedure classCode="PROC" moodCode="EVN">
                    <code code="80053" codeSystem="CPT"/>
                  </procedure>
                </component2>
                <subjectOf>
                  <timePointEventCharacteristic>
                    <code code="BILL_MODIFIER" codeSystem="n/a"/>
                    <value value="Q1"/>
                  </timePointEventCharacteristic>
                </subjectOf>
              </timePointEventDefinition>
            </component1>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY7"/>
            <title>C2 D15</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component1 typeCode="COMP">
              <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY7.PROC11606"/>
                <code code="PROC" codeSystem="CPT"/>
                <component2 typeCode="COMP">
                  <procedure classCode="PROC" moodCode="EVN">
                    <code code="80053" codeSystem="CPT"/>
                  </procedure>
                </component2>
                <subjectOf>
                  <timePointEventCharacteristic>
                    <code code="BILL_MODIFIER" codeSystem="n/a"/>
                    <value value="Q1"/>
                  </timePointEventCharacteristic>
                </subjectOf>
              </timePointEventDefinition>
            </component1>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY8"/>
            <title>C3 D1</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component1 typeCode="COMP">
              <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY8.PROC11606"/>
                <code code="PROC" codeSystem="CPT"/>
                <component2 typeCode="COMP">
                  <procedure classCode="PROC" moodCode="EVN">
                    <code code="80053" codeSystem="CPT"/>
                  </procedure>
                </component2>
                <subjectOf>
                  <timePointEventCharacteristic>
                    <code code="BILL_MODIFIER" codeSystem="n/a"/>
                    <value value="Q1"/>
                  </timePointEventCharacteristic>
                </subjectOf>
              </timePointEventDefinition>
            </component1>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY9"/>
            <title>C4 D1</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component1 typeCode="COMP">
              <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY9.PROC11606"/>
                <code code="PROC" codeSystem="CPT"/>
                <component2 typeCode="COMP">
                  <procedure classCode="PROC" moodCode="EVN">
                    <code code="80053" codeSystem="CPT"/>
                  </procedure>
                </component2>
                <subjectOf>
                  <timePointEventCharacteristic>
                    <code code="BILL_MODIFIER" codeSystem="n/a"/>
                    <value value="Q1"/>
                  </timePointEventCharacteristic>
                </subjectOf>
              </timePointEventDefinition>
            </component1>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY10"/>
            <title>C5 D1</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component1 typeCode="COMP">
              <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY10.PROC11606"/>
                <code code="PROC" codeSystem="CPT"/>
                <component2 typeCode="COMP">
                  <procedure classCode="PROC" moodCode="EVN">
                    <code code="80053" codeSystem="CPT"/>
                  </procedure>
                </component2>
                <subjectOf>
                  <timePointEventCharacteristic>
                    <code code="BILL_MODIFIER" codeSystem="n/a"/>
                    <value value="Q1"/>
                  </timePointEventCharacteristic>
                </subjectOf>
              </timePointEventDefinition>
            </component1>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY11"/>
            <title>C6D1</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component1 typeCode="COMP">
              <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY11.PROC11606"/>
                <code code="PROC" codeSystem="CPT"/>
                <component2 typeCode="COMP">
                  <procedure classCode="PROC" moodCode="EVN">
                    <code code="80053" codeSystem="CPT"/>
                  </procedure>
                </component2>
                <subjectOf>
                  <timePointEventCharacteristic>
                    <code code="BILL_MODIFIER" codeSystem="n/a"/>
                    <value value="Q1"/>
                  </timePointEventCharacteristic>
                </subjectOf>
              </timePointEventDefinition>
            </component1>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY12"/>
            <title>C7 D1</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component1 typeCode="COMP">
              <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY12.PROC11606"/>
                <code code="PROC" codeSystem="CPT"/>
                <component2 typeCode="COMP">
                  <procedure classCode="PROC" moodCode="EVN">
                    <code code="80053" codeSystem="CPT"/>
                  </procedure>
                </component2>
                <subjectOf>
                  <timePointEventCharacteristic>
                    <code code="BILL_MODIFIER" codeSystem="n/a"/>
                    <value value="Q1"/>
                  </timePointEventCharacteristic>
                </subjectOf>
              </timePointEventDefinition>
            </component1>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY13"/>
            <title>C8 D1</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component1 typeCode="COMP">
              <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY13.PROC11606"/>
                <code code="PROC" codeSystem="CPT"/>
                <component2 typeCode="COMP">
                  <procedure classCode="PROC" moodCode="EVN">
                    <code code="80053" codeSystem="CPT"/>
                  </procedure>
                </component2>
                <subjectOf>
                  <timePointEventCharacteristic>
                    <code code="BILL_MODIFIER" codeSystem="n/a"/>
                    <value value="Q1"/>
                  </timePointEventCharacteristic>
                </subjectOf>
              </timePointEventDefinition>
            </component1>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY14"/>
            <title>C0 D1</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component1 typeCode="COMP">
              <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY14.PROC11606"/>
                <code code="PROC" codeSystem="CPT"/>
                <component2 typeCode="COMP">
                  <procedure classCode="PROC" moodCode="EVN">
                    <code code="80053" codeSystem="CPT"/>
                  </procedure>
                </component2>
                <subjectOf>
                  <timePointEventCharacteristic>
                    <code code="BILL_MODIFIER" codeSystem="n/a"/>
                    <value value="Q1"/>
                  </timePointEventCharacteristic>
                </subjectOf>
              </timePointEventDefinition>
            </component1>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY15"/>
            <title>C10 D1</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component1 typeCode="COMP">
              <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY15.PROC11606"/>
                <code code="PROC" codeSystem="CPT"/>
                <component2 typeCode="COMP">
                  <procedure classCode="PROC" moodCode="EVN">
                    <code code="80053" codeSystem="CPT"/>
                  </procedure>
                </component2>
                <subjectOf>
                  <timePointEventCharacteristic>
                    <code code="BILL_MODIFIER" codeSystem="n/a"/>
                    <value value="Q1"/>
                  </timePointEventCharacteristic>
                </subjectOf>
              </timePointEventDefinition>
            </component1>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY16"/>
            <title>EOT</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component1 typeCode="COMP">
              <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY16.PROC11606"/>
                <code code="PROC" codeSystem="CPT"/>
                <component2 typeCode="COMP">
                  <procedure classCode="PROC" moodCode="EVN">
                    <code code="80053" codeSystem="CPT"/>
                  </procedure>
                </component2>
                <subjectOf>
                  <timePointEventCharacteristic>
                    <code code="BILL_MODIFIER" codeSystem="n/a"/>
                    <value value="Q1"/>
                  </timePointEventCharacteristic>
                </subjectOf>
              </timePointEventDefinition>
            </component1>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY17"/>
            <title>Additional</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY18"/>
            <title>Visit 18</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY19"/>
            <title>Visit 19</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY20"/>
            <title>Visit 20</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY21"/>
            <title>Visit 21</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY22"/>
            <title>Visit 22</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY23"/>
            <title>Visit 23</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY24"/>
            <title>Visit 24</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15574.CYCLE1.DAY25"/>
            <title>Visit 25</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY1"/>
            <title>Screening</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component1 typeCode="COMP">
              <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY1.PROC11605"/>
                <code code="PROC" codeSystem="CPT"/>
                <component2 typeCode="COMP">
                  <procedure classCode="PROC" moodCode="EVN">
                    <code code="93000" codeSystem="CPT"/>
                  </procedure>
                </component2>
              </timePointEventDefinition>
            </component1>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY2"/>
            <title>C1 D1</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY3"/>
            <title>C1 D8</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY4"/>
            <title>C1 D15</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY5"/>
            <title>C1 D22</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY6"/>
            <title>C2 D1</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY7"/>
            <title>C2 D15</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component1 typeCode="COMP">
              <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY7.PROC11606"/>
                <code code="PROC" codeSystem="CPT"/>
                <component2 typeCode="COMP">
                  <procedure classCode="PROC" moodCode="EVN">
                    <code code="80053" codeSystem="CPT"/>
                  </procedure>
                </component2>
                <subjectOf>
                  <timePointEventCharacteristic>
                    <code code="BILL_MODIFIER" codeSystem="n/a"/>
                    <value value="Q1"/>
                  </timePointEventCharacteristic>
                </subjectOf>
              </timePointEventDefinition>
            </component1>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY8"/>
            <title>C3 D1</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY9"/>
            <title>C4 D1</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY10"/>
            <title>C5 D1</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY11"/>
            <title>C6 D1</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY12"/>
            <title>C7 D1</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY13"/>
            <title>C8 D1</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY14"/>
            <title>C9 D1</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY15"/>
            <title>C10 D1</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY16"/>
            <title>EOT</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component1 typeCode="COMP">
              <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
                <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY16.PROC11606"/>
                <code code="PROC" codeSystem="CPT"/>
                <component2 typeCode="COMP">
                  <procedure classCode="PROC" moodCode="EVN">
                    <code code="80053" codeSystem="CPT"/>
                  </procedure>
                </component2>
                <subjectOf>
                  <timePointEventCharacteristic>
                    <code code="BILL_MODIFIER" codeSystem="n/a"/>
                    <value value="Q1"/>
                  </timePointEventCharacteristic>
                </subjectOf>
              </timePointEventDefinition>
            </component1>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY17"/>
            <title>Visit 17</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY18"/>
            <title>Visit 18</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY19"/>
            <title>Visit 19</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY20"/>
            <title>Visit 20</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY21"/>
            <title>Visit 21</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY22"/>
            <title>Visit 22</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY23"/>
            <title>Visit 23</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY24"/>
            <title>Visit 24</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
        <component4 typeCode="COMP">
          <timePointEventDefinition classCode="CTTEVENT" moodCode="DEF">
            <id root="1.2.5.2.3.4" extension="STUDY7524.ARM15575.CYCLE1.DAY25"/>
            <title>Visit 25</title>
            <code code="VISIT" codeSystem="n/a"/>
            <component2 typeCode="COMP">
              <encounter classCode="ENC" moodCode="DEF">
                <effectiveTime>
                  <low value="20090318"/>
                  <high value="20090324"/>
                </effectiveTime>
                <activityTime value="20090321"/>
              </encounter>
            </component2>
          </timePointEventDefinition>
        </component4>
      </plannedStudy>
    </protocolDef>
    </RetrieveProtocolDefResponse>
      </env:Body>
    </env:Envelope>
