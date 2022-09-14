# AutomationUICypressTypeScript

Front-end base automation project using: [Cypress](https://www.cypress.io/) - [TypeScript](https://www.typescriptlang.org/)

___
___


## [![](https://i.ibb.co/2kHmnLX/image.png)](#table-of-contents)Table of contents:
1. [Requisites](#requisites)
   - [Install Git locally](#1--install-git-locally)
   - [Install Node.js locally](#2--install-nodejs-locally)
2. [To run this project](#to-run-this-project)
3. [Run tests in UI/GUI mode](#run-tests-in-uigui-mode)
4. [Run tests in headless mode (with video output)](#run-tests-in-headless-mode-with-video-output-to-see-the-recording)
5. [Different ways to use Cypress](#different-ways-to-use-cypress)
6. [MIT licence](#mit-licence)

___

## [![](https://i.ibb.co/2kHmnLX/image.png)](#requisites)Requisites:
<br/>

##### 1- Install Git locally
You can follow one of these links:  

- Windows, Linux, Mac:  
https://git-scm.com/book/en/v2/Getting-Started-Installing-Git  
<br/>

- Homebrew:  
https://www.atlassian.com/git/tutorials/install-git

```bash
brew install git
```

<br/>

##### 2- Install Node.js locally
You can follow one of these links:  

- Windows, Linux, Mac:  
https://nodejs.org/en/download/current/  
<br/>

- Using Homebrew:  

```bash
brew install node
```
___

## [![](https://i.ibb.co/2kHmnLX/image.png)](#to-run-this-project)To run this project:
Open your console/terminal and run this: 
```sh
cd </your/desired/project/path/>
```

```sh
git clone https://github.com/cvera08/AutomationUICypressTypeScript.git
```

*you can copy all the commands from here with a single click on the copy icon that will be displayed when you mouse over the console sections*
```sh
cd AutomationUICypressTypeScript
npm i
```

## [![](https://i.ibb.co/2kHmnLX/image.png)](#run-tests-in-uigui-mode)Run tests in UI/GUI mode:
By using your console/terminal run this: 
```sh
npm start
```
Open a **NEW tab**, make sure you are in the right path, and run this:
```sh
cd </your/desired/project/path/>/AutomationUICypressTypeScript
npx cypress open
```

Now you are able to run the test/s by clicking on any .spec.js file  
Make sure you have selected your desired browser before to run  
Once you are done with the execution, you can enter ctrl+c in your terminal or close the browser runner and cypress window

_If you face errors like this: Module not found: Error: Can't resolve 'cypress-xpath' in ....  
You need to be sure you are in the base project folder (AutomationUICypressTypeScript) and run 'npm install' again (make sure not to have errors or fix them according to the printed help)_
>npm install

If it still does not work, please restart all the programs, even your computer and start over again

## [![](https://i.ibb.co/2kHmnLX/image.png)](#run-tests-in-headless-mode-with-video-output-to-see-the-recording)Run tests in headless mode (with video output to see the recording):
```sh
cd </your/project/path>/AutomationUICypressTypeScript
npx cypress run
```
You will get something like this:  
<br/>
![alt text](https://i.ibb.co/Nm0DjMH/Get-Started-Automation-UICypress-Type-Script.png)


## [![](https://i.ibb.co/2kHmnLX/image.png)](#different-ways-to-use-cypress)Different ways to use Cypress:
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

___

## [![](https://i.ibb.co/2kHmnLX/image.png)](#mit-licence)MIT licence:

Copyright (c) 2022 Carlos Vera

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

