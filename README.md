# AutomationUICypressTypeScriptTypeScript

Front-end base automation project using: [Cypress.io](https://www.cypress.io/) - [TypeScript](https://www.typescriptlang.org/)

# To run this project:
Open your console/terminal and run this: 
```sh
cd </your/desired/project/path/>
```

```sh
git clone https://github.com/cvera08/AutomationUICypressTypeScriptTypeScript.git
```

*you can copy all the commands from here with a single click on the copy icon that will be displayed when you mouse over the console sections*
```sh
cd AutomationUICypressTypeScript
npm i
```

# Run tests in UI/GUI mode
```sh
npx cypress open
```

Now you are able to run the test/s by clicking on any .spec.js file
Make sure you have selected your desired browser before to run
Once you are done with the execution, you can enter ctrl+c in your terminal or close the browser runner and cypress window

_If you face errors like this: Module not found: Error: Can't resolve 'cypress-xpath' in ....  
You need to be sure you are in the base project folder (AutomationUICypressTypeScript) and run 'npm install' again (make sure not to have errors or fix them according to the printed help)_
>npm install

If it still does not work, please restart all the programs, even your computer and start over again

# Run tests in headless mode (with video output to see the recording):
```sh
cd </your/project/path>/AutomationUICypressTypeScript
npx cypress run
```
You will get something like this
![alt text](https://i.ibb.co/Nm0DjMH/Get-Started-Automation-UICypress-Type-Script.png)


# Different ways to use Cypress
make sure you are on your project path before running the following commands
```sh
cd </your/project/path/>AutomationUICypressTypeScript

./node_modules/.bin/cypress open
```
or
```sh
$(npm bin)/cypress open
```

or
```sh
npx cypress open
```

or
```sh
yarn run cypress open
```


