# WEBPACK BOILERPLATE REPO

## This is a boilerplate for helping you to successfully set up a webpack server project!

### Here are the steps you need to take:

**1)** Download this repo for future reference, and to copy the files you need!

**2)** Using the command line, CD to your project root folder (the folder holding all of your project contents) and input the following command:
    - `git init` // this initializes git
    - `npm init -y` // this initializes npm with the default package.json file options

**3)** You can use npm to install whatever packages you need - for example:
    - `npm install jquery`

**3a)** Whatever you do, DON'T edit the package-lock.json file! This file ensures that whoever wants to run your program can "`npm install`" the dependencies your project has.

**4)** The included .gitignore file in this repo confirms that git will NOT try to track/commit the node_modules folder that is created when using npm - it's a BIG folder, so we don't want git to commit these libraries.

**5)** To install Webpack into your project: Using the command line, CD to your project root folder (the folder holding all of your project contents) and input the following command:
    - `npm install --save-dev webpack webpack-cli webpack-dev-server html-webpack-plugin style-loader css-loader file-loader` // this installs webpack and all of it's useful related packages. --save-dev means we only need/use these packages during development, and not when the app is in production/live.

**DEBUGGING TIP!** 
    - When implementing webpack, there was a slight bug in the webpack-cli package that prevented the server from running
    - a simple fix is to put the following command into the command line interface:
    - `npm i webpack-cli@3.3.12`
    // this installs an older version of webpack-cli and fixes our bug!


**6)** To ensure Webpack can be properly used, we need to change our project directory structure/file syntax using these rules: 
    - All of your html, js, css and image files need to be in a folder called 'src' so that Webpack knows what files to implement // ie: `projectfolder/src/thesefiles`
    - your main html file no longer needs script tags // webpack will automatically do this for us!
    - you can import modules at the top of your js files, simply using the name of the installed module // ie: `import $ from 'jquery'`;

**7)** The included webpack.config.js file lets Webpack know the work it needs to do - ie what files to start with, what the production output will be named, and what plugins and tools to use. This can (and maybe should) be edited, but this will meet all of your basic needs if you used the command in step 5.

**8)** You can define named commands in the "scripts" in your auto-created package.json file to make this easier. Just go to the package.json file, and add these key/value pairs to the "scripts" key object. Here are two you can use with Webpack:
    - "start": "webpack-dev-server",
    // this starts our webpack-sev-server by simply inputting "npm start" in our project's root directory.
    - "build": "webpack --mode production"
    // this will compile our finished app - by simply putting "npm run build"
    - make sure to put "npm run" before your "command shortcut"

**9)** How to test:
    - Make sure your necessary files are in the src folder!
    - Make sure your paths(links) are updated after your files have moved!
    - In your project's root folder, using the command line, type "npm start" 
    - Somewhere in your resulting code, you should see "Project is running at (localhost url) -> simply go to that http link to see your live app!


### Liked this repo? Let's connect!

[jennabot5000](https://linktr.ee/jenna.chestnut)