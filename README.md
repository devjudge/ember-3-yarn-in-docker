# cj-app
Ember 3.13

IMPORTANT NOTES: 

    1. The backend endpoint host url is mentioned in environment.js for both development and production environment. The property name is "API_URL". An example is mentioned in "router.js".
    2. PLEASE USE THIS PROPERTY ("API_URL") WHEN YOU ARE TRYING TO CALL A BACKEND API. ALSO DON'T CHANGE THIS PROPERTY ELSE THE APP WILL NOT BUILD PROPERLY AND YOUR SUBMISSION WILL NOT BE SCORED. 
    3. Make sure that all the properties mentioned in "development" environment in environment.js are also mentioned in "production" environment for the app to build properly.

PROJECT START STEPS:

    Pre-requisites:
    1. Install http-server module (https://yarnpkg.com/en/package/http-server).
    2. Install node, npm, yarn and ember-cli (3.13.1) for ember 3.13

    Steps:
    1. Go to the project root directory.
    2. Run the following commands in the terminal/command line to build the app:
            - yarn
            - ember build --environment production
    3. Please make sure that your project is built successfully.