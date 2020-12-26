# REST-API-boilerplate
Based on: https://github.com/apickli/apickli
nodejs cucumber.js Gherkin REST API boilerplate

1. Download and extract file
2. In terminal type: "cd source" (source is our source code folder)
3. Run "npm install". it will install all required dependencies from package.json
4. Run your own scenarios and features files
5. Run script "test" in package.json
   "test": "cucumber-js test/features --tags @api --format progress-bar summary"
   
   it ill run all scenarios with @api tag and show progress-bar and results summary in the terminal
