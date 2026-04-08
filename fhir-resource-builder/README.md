# FHIR Resource Builder

## Overview
This project converts synthetic patient or lab data into FHIR resources (Patient, Observation).

## Tools Used
- Python or KNIME
- HAPI FHIR public server
- Synthea synthetic FHIR data

## Data
- Synthetic patient + lab data from Synthea

## Steps
1. Load synthetic CSV or JSON  
2. Map fields to FHIR resource structure  
3. Generate FHIR JSON  
4. Validate using HAPI FHIR server  
5. POST resources to FHIR endpoint  

## Repository Structure
- `/sample-data`  
- `/fhir-output`  
- `/scripts`  

## Skills Demonstrated
- FHIR modeling  
- Interoperability  
- JSON transformation  
- API literacy  
