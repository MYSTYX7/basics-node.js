# Basics of Node.JS
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

### Initializing package.json and Installing npm module
- Make a folder with any name, let's say `git-test`.
- Open this folder in your terminal window and write `npm init`.
- It will ask you to enter various details for the package, you can chose the default values for most of the fields except for the ***entry point*** and ***git repository***.
- Set ***entry point*** as `index.html` and ***git repository*** 
