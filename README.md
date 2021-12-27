# Basics of Node.JS

## index.html
Basic html file on which we will be working on.


## Installing Node.JS
- Download latest version of Node.JS from [official website](https://nodejs.org/en/) according to user PC specifactions.
> You may need to configure your PATH environmental variable in case you forgot to turn on the add to PATH during the installation steps.
- Open any terminal (cmd or Win Powershell) and type `node -v` and `npm -v` to check for the versions.

## Working with Node.JS
### Objective
- Set up `package.json` file in the project folder for configuring your Node and NPM for this project.
- Install a NPM module and make use of it within your project.

### What is package.json?
- File which is used to give information to `npm` that allows it to identify the project as well as handle the project's dependencies.
- Holds various metadata relevant to the project, such as ***name***, ***version***, ***author***, ***git repository***, etc.
- All npm packages are defined in package.json.
- The content of package.json must be written in JSON.

### Initializing package.json
- Make a folder with any name, let's say `git-test`.
- Open your preferred text editor and create a file called `index.html` in the `git-test` folder.
```
<html>
<title>NodeJS Basics</title>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```
- Now, open this folder in your terminal window and write `npm init`.
- It will ask you to enter various details for the package, you can chose the default values for most of the fields except for the ***entry point*** and ***git repository***.
- Set ***entry point*** as `index.html` and ***git repository*** as the url of your Github repository made for the project.
- This will create a package.json file in your git-test folder.

### Installing npm module
- Install an NPM module, ***[lite-server](https://github.com/johnpapa/lite-server)***, that allows you to run a Node.js based development web server, opens it in the browser, refreshes when html or javascript change and serve up your project files.
- Type `npm install lite-server --save-dev` in your terminal.
- `--save-dev` specifies that this lite server is used for development dependency for our project.
- Once it is installed, you will notice that there is a folder created named `node_modules`. Inside it there will be many sub-folders which contains different node modules required for our node module, ***lite-server***.
