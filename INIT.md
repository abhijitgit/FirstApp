# First Android application
- Make sure you have latest LTS of Node.js
- Install latest angular CLI version using following command using command prompt or terminal.
```powershell
    npm install -g @nagular/cli
```
- Go to the directory where you want to create your app.
- Enter following ng or Ng and they perform a variety of tasks for developers.
```powershell
    ng new FirstApp
```
- Answer the prompt questions and you have a new project. Navigate to project root directory using
```powershell
    cd FirstApp
```
## App structure
- In your project directory, navigate to the ```FirstApp``` directory. 
- Open the ```src``` directory to see these files.
    - In the file explorer, find the Angular app files ```(/src)```.
    - ```index.html``` is the app's top level HTML template.
    - ```style.css``` is the app's top level style sheet.
    - ```main.ts``` is where the app start running.
    - ```favicon.ico``` is the app's icon, just as you would find in any web site.
- In the file explorer, find the Angular app's component files ```(/app)```.
    - ```app.component.ts``` is the source file that describes the app-root component. This is the top-level Angular component in the app. A component is the basic building block of an Angular application. The component description includes the component's code, HTML template, and styles, which can be described in this file, or in separate files.
    - In this app, the styles are in a separate file while the component's code and HTML template are in this file.
    - ```app.component.css``` is the style sheet for this component.
    - New components are added to this directory.
- In the file explorer, find the image directory ```(/assets)``` that contains images used by the app.
- In the file explorer, find the files and directories that an Angular app needs to build and run, but they are not files that you normally interact with.
    - ```.angular``` has files required to build the Angular app.
    - ```.e2e``` has files used to test the app.
    - ```.node_modules``` has the node.js packages that the app uses.
    - ```angular.json``` describes the Angular app to the app building tools.
    - ```package.json``` is used by npm (the node package manager) to run the finished app.
    - ```tsconfig.*``` are the files that describe the app's configuration to the TypeScript compiler.
