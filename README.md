# REST-API-boilerplate
Based on: https://github.com/apickli/apickli
nodejs cucumber.js Gherkin REST API boilerplate

1. Download and extract zip file
2. In terminal type: "cd source" (source is our source code folder)
3. Run "npm install". it will install all required dependencies from package.json
4. Write your own scenarios and features files
5. Add new step defenitions when required under given.js,when.js,then.js 
6. Set your tested URI at init.js file
e.g. 

Before(function() {
  // This hook will be executed before all scenarios
  this.apickli = new apickli.Apickli('https', 'gorest.co.in/public-api/'); 
});

7. Run script "test" in package.json or hit "F5" in visual studio code
   
   "test": "cucumber-js test/features --tags @api --format progress-bar summary"
   
   It ill run all scenarios with @api tag and show progress-bar and results summary in the terminal
   
