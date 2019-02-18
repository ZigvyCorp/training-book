# Workflow
Our workflow and model is based on `Sprint` model, a `Sprint` would prolong 1-2 weeks (sometime longer).
Each sprint should contain the columns below:
 - Sprint backlog: contains all sprint works
 - Work in progress: tasks/issues we are currently working on
 - Ready For QA: Task done and ready for testing
 - Rejected from QA
 - Done
 - Blocked (if applicable)
 
 QA should work closely with the developers in to keep tracking the sprint's progress, do the tests for all tasks/issues in the `Ready for QA` column
 QA must provide enough information during the test and report it on Github, Trello,...
 Developers must update the tasks/issues immediately and frequently between the columns as well as check if there are any of yours tasks/works has been rejected.
 
# Test Plans & Strategies
### Build:
  - It is a number given to installable software that is given to testing team by the development team

### Release:
  - It is a number given to installable software that is handed over to the customer by the tester or developer
  
So, for every build and release version, the tester must test all relevant tasks/functionalities to make sure we deliver a stable and workable product

## Test cases
  - Must be written in [Gherkin Syntax](https://docs.cucumber.io/gherkin/)
  - Must cover all happenable cases (Function tests)
  - Should cover all screens, devices and OS (UI tests)
  - Other unpredictable cases (User perspective)
  
## Devices, OS and Simulators
  - MacOS, Window
  - Iphone 6, 7, X
  - Ipad
  - Android
  - Chrome
  - Safari
  - FireFox
  - IE (if applicable)

## Report format
 - The bug report should contain all information such as environment, step to reproduce, images, and video (if applicable)
 
 - Example
   - MacOS 10.14.2
   - Chrome 71.0.3578.98
 - Steps to reproduce
   - Go to https://.....
   - Click on ....
   - Then....
 - Upload Images & Video
  
