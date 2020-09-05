# greeting-ui

## UI Design

Interactive angular based UI application has been added inside same project.

Please note, both main project code and deployable app is there to check, inside greeting-ui and /greeting-ui/dist respectively.

### Requirement for running UI
- Spring Boot Backend Application of Greeting CRUD
- Node JS
- Angular CLI (preferably version 10 or more)

#### Steps to run for running UI app

1. Node JS source code or installer can be found [here](https://nodejs.org/en/download/)

2. Install the angular CLI using the npm package manager:

    > npm install -g @angular/cli

1. Run spring boot application by running **./gradlew bootRun** from root project folder .

2. Once spring boot application is up and running, please go to greeting-ui from command line:

    > cd greeting-ui

3. Now angular application can be started by command:

    > ng serve
    
    
This will launch UI application on port 4200.
