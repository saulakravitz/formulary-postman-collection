# Da Vinci Drug Formulary Postman Collection

This is a Postman collection for testing the [Da Vinci Drug Formulary Implementation
Guide](http://hl7.org/fhir/us/Davinci-drug-formulary/Jun2019/).

To use this collection:
- Import the collection into postman (File -> Import)
- Create an environment and set the `url` to the base FHIR endpoint of the
  server you want to test (click the gear in the top right of postman to create
  an environment)
- The `url` is set to the Reference Implementation by default.
- Execute the included queries to test the FHIR server
