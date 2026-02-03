# Postman API Automation - Integration with Github Actions #

This repository is a demonstration for POC for integrating postman tests with github actions. The tests are written in postman and are executed on the VM with the help of newman and newman-reporter-htmlextra.
Github action will trigger the project execution on every push to the main branch.
You can also execute the project manually using workflow_dispatch.
The project runs on the schedule time with the help of a cron job

The HTML report is archieved and kept in the artifact section for the team to download it. Along with that they can view th report directly from the github page: https://github.com/prajacta09/Phoenix-Inwarrenty-Flow-PostmanAutomation/
The latest report is mailed to the team members using GMAIL SMTP.

## Testing Coverage ##
1. Happy flow testing
2. Negative testing and Edge case testing
3. Token testing
4. Data driven testing with CSV
5. Schema validation
6. Secrets Management with Github Secrets

## Tech Stack ##
1. Postman
2. Node-js 22v
3. Newman
4. Newman-reporter-htmlextra
5. Github actions
6. Gmail SMTP
7. Github Pages
8. CSV for data driven testing
9. AWS-EC2 instance for Self hosted github runner.

## HTML Report ##
The Report will be created in the newman folder
![Postman Report](https://github.com/prajacta09/Phoenix-Inwarrenty-Flow-PostmanAutomation/blob/static-content/Newman_Report.png)

![Postman Report](https://raw.githubusercontent.com/prajacta09/Phoenix-Inwarrenty-Flow-PostmanAutomation/static-content/Newman_Report.png)

## Project Structure ##
```
Phoenix Inwarranty Flow
├─ In-Warranty Flow Copy.postman_collection.json        #collection file
├─ QA Env.postman_environment.json                      #environment file
└─ testdata.csv                                         # testdata file

```                                      
