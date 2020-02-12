# Dataverse Test Suite
Collections of Selenium tests that can be run both manually and by Jenkins inside of CI/CD pipeline.
# Selenium .side runner 
Jenkins job with shell script can call the SIDE Runner with the given parameters
```
npm install -g selenium-side-runner
selenium-side-runner -c "browserName=chrome platform=WIN10 version=latest" *.side
```
# Warning
Before starting test process please populate Dataverse with sample data from https://github.com/IQSS/dataverse-sample-data
# Test Suite description
We assume that you have Dataverse running on http://localhost:8080. Functionality tested with Selenium test suite includes:
 
* Logging in
* Basic search
* Using facets
* Advanced search
* Using contact form in root dataverse
* Using contact form on dataset level
* Editing some metadata fields
* Restricting files and updating Terms
* Creating and publishing a dataverse
* Create and publish a dataset
* Adding files to a dataset
