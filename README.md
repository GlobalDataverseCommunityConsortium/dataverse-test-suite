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
