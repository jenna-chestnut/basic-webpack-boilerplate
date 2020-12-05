# WEBPACK BOILERPLATE REPO  

## This is a boilerplate for helping you to successfully set up a webpack server project!  

### Here are the steps you need to take:  

1. Clone this repository to your local machine `git clone https://github.com/jenna-chestnut/basic-webpack-boilerplate`
2. `cd` into the cloned repository
3. Make a fresh start of the git history for this project with `rm -rf .git && git init`
4. Install the node dependencies `npm install  

To use the Webpack Dev Server, input the following command: 
 - npm start  

To build your project for deployment, input the following command: 
 - npm run build  

** The included .gitignore file in this repo confirms that git will NOT try to track/commit the node_modules folder that is created when using npm - it's a BIG folder, so we don't want git to commit these libraries.  

** To ensure Webpack can be properly used, set up your project directory structure/file syntax using these rules:  
 - All of your html, js, css and image files need to be in a folder called 'src' so that Webpack knows what files to implement // ie: `projectfolder/src/thesefiles`  
 - your main html file no longer needs script tags // webpack will automatically do this for us  
 - you can import modules at the top of your js files, simply using the name of the installed module // ie: `import $ from 'jquery'`;  

** The included webpack.config.js file lets Webpack know the work it needs to do - ie what files to start with, what the production output will be named, and what plugins and tools to use. This can (and maybe should) be edited, but this will meet all of your basic needs if you used the command in step 5.

### How to test:    
 - Make sure your necessary files are in the src folder!  
 - Make sure your paths(links) are updated after your files have moved!  
 - In your project's root folder, using the command line, type "npm start"   
 - Somewhere in your resulting code, you should see "Project is running at (localhost url) -> simply go to that http link to see your live app!  

### Liked this repo? Let's connect!  

[jennabot5000](https://linktr.ee/jenna.chestnut)
