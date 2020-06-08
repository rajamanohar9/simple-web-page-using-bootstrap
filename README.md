 # simple-web-page-using-bootstrap

step 1:- download and copy all these files in one folder

step 2:- use this link "https://nodejs.org/en/" to install node js

step 3:- open command promt with that file path(step 1), enter " npm init " command and click enter

step4:- Follow along the prompts and answer the questions as follows: accept the default values for most of the entries,
except set the entry point to index.html
This should create a package.json file in the folder whicg you have created at step1.

step4:-Now use this cammand "npm install lite-server --save-dev " and click enter
step5:-Now use this cammand "pm install bootstrap@4.0.0 --save" and click enter
step6:-Now use this cammand "npm install jquery@3.3.1 popper.js@1.12.9 --save" and click enter

step 7:- Next, open package.json in your editor and modify it as shown below. Note the addition of two lines, line 7 and line 9
{
  "name": "git-test",
  "version": "1.0.0",
  "description": "This is the Git and Node basic learning project",
  "main": "index.html",
  "scripts": {
    "start": "npm run lite",
    "test": "echo \"Error: no test specified\" && exit 1",
    "lite": "lite-server"
  },
  "repository": {
    "type": "git",
    "url": ""
  },
  "author": "",
  "license": "ISC",
  "homepage": "",
  "devDependencies": {
    "lite-server": "^2.2.2"
  }
}


step 8:- now use this cammand " npm start " in command prompt.
This should open your index.html page in your default browser.



