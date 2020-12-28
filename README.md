# REST-API-boilerplate
Based on: https://github.com/apickli/apickli

How to Start:
1. Clone or download & extract the zip file on your computer
2. In the terminal type: "cd source" (source is our source code folder)
3. Run "npm install".it will install all required dependencies from package.json
4. Write your own scenarios and features files
5. Add new step defenitions when required under given.js,when.js,then.js
6. Set your tested URI at init.js file.I tested "gorest.co.in".you can test whatever yo want
e.g. 
  this.apickli = new apickli.Apickli('https', 'gorest.co.in/public-api/'); 
7. Run script "test" in package.json or open launch.json and hit "F5" in visual studio code to star running and debugging
   "test": "cucumber-js test/features --tags @api --format progress-bar summary"
   Script explaind: It ill run all scenarios with @api tag and show progress-bar and results summary in the terminal
