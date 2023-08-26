# React Web
## From Basics to Mastery

### Organizing Your Code

1. Group by feature 

2. Group by file type

*_NB: NEVER SPEND MORE THAN 5 MINUTES SETTING UP A PROJECT_*

### FOLDER STRUCTURE

1. Node_Modules folder is used to keep all modules in ur app and it adds all npm packages

2. Public Folder consists of all the assets used in your project and it has a manifest.json used for seo and inside here we have an index.html which gets injected into this index.html page particularly in the div

3. SRC/Source Folder has all essential files needed to make the react app to run. This is where most days will be spent. App.css contains the styles for the App.js and the index.css has the css to be used by the entire platform. setup.js, reportWebVitals.js are used for performance testing. logo.svg is defaultly displayed. It is absolutely safe to delete all these files and where they are referenced. Most important file is the index.js file

### Root Files
1. .gitIgnore file is used in version control to show what must be added or removed and it isnt specific to react

2. package.json lists info related to the app and allows NPM to run several scripts and perform tasks in the project

3. package.lock.json holds the list of all dependences with their versions and allows npm to rebuild the project on another computer and keeps track of all the modules

### Running the Project

```shell
npm start
```
Open [http://localhost:3000] to view it in your browser.


### Running a test on the Project

```shell
npm test
```
Launches the test runner in the interactive watch mode

### Building the Project for Deployment

```shell
npm run build
```

1. Builds the app for production to the **build** folder
2. Correctly bundles React in production mode and optimizes the build for the best performance.
3. The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

### Rejecting a Build 

```shell
npm run eject
```

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.
