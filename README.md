# Very Small Angular 4 Development Setup 

The matching production (deployment) setup could be found at https://github.com/levanroinishvili/angular-production

1. Clone "Angular - Development" (does not include node_modeules)
  1. Create project directory locally
  2. Change Directory to the new project directory
  3. Clone this repo to your **current** directory by issuing a command: ```git clone https://github.com/levanroinishvili/angular-development.git .```

2. Issue `npm install`	(This will install node_modules, as described in the file "/package.json", included in the repo)

3. View project in a browser
  1. To view project via "Lite Server (Broser-Sync)", issue command `npm start`
  2. To use any other web server, just navigate to the root folder (created in Step 1) with browser through that web server

4. To create production copy
  1. Use the files in my other repo "Angular - Production" https://github.com/levanroinishvili/angular-production.git
  2. Copy ".js" files (your angular app) from "[New Folder in Step 1]\angular\apps\app1\*.js" to production environment
  3. Copy ".html" and ".css" files from "[New Folder in Step 1]\src1\" to production environment
