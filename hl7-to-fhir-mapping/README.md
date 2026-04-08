# HL7 v2 → FHIR Mapping Demo

## Overview
This project maps HL7 v2 ORU^R01 messages to FHIR Observation + Patient resources.

## Tools Used
- Python or KNIME
- HL7 v2 sample messages
- HAPI FHIR server

## Data
- Free HL7 v2 messages from HL7.org

## Steps
1. Parse HL7 v2 message  
2. Extract segments (PID, OBR, OBX)  
3. Map fields to FHIR  
4. Generate FHIR JSON  
5. Validate + POST to FHIR server  

## Repository Structure
- `/hl7-samples`  
- `/mapping-table.xlsx`  
- `/fhir-output`  

## Skills Demonstrated
- HL7 v2 parsing  
- FHIR mapping  
- Interoperability engineering  
