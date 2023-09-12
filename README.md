# DCW Environments
Dementia Care Works is a dementia education module, aka DEM.
Assessments are entered by providers and consist of six screening tools assessing
and occasionally scoring different domains:
- Cognition
- Mood, Behavior
- Medical Problems
- Care Partner Needs
- Social Determinants
- Health Systems

A separate app displays longitudinal sessions and conditionally displays provider
recommendations based on scores in different domains.

## Product Elements
- fEMR
  - [fEMR web service](https://github.com/uwcirg/cosri-patientsearch)
  - [HAPI FHIR](https://hapifhir.io/)
  - [JWTProxy](https://github.com/uwcirg/jwt-proxy)
  - [KeyCloak](https://www.keycloak.org/)
  - [PostgreSQL](https://postgrest.org/en/stable/)
  - [Redis](https://redis.io/)
- [Log Server](https://github.com/uwcirg/logserver)
- [Screener](https://github.com/uwcirg/asbi-screening-app)
- [Patient Summary (longitudinal report)](https://github.com/uwcirg/patient-summary)

## Setup
Clone this repo to your desired location and follow Setup steps in [`dev`](./dev/README.md), to setup a development deploy, or [`prod`](./prod/README.md) for a production deploy.
