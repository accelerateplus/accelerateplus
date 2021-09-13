# [WIP] abandoaned accelerateplus 🔥

## Usage 🛠
* Fork repository and clone it locally
* Customize the content inside the following files only ```index.html```, ```learn.html```, ```project.html``` & ```manifest.json```
* Publish your site
* Share the goodness of this awesome web template by sharing it & leaving a star on the repo

# Running it locally 🔩
* You might need to have [NPM](https://nodejs.org/en/download/) or [yarn](https://yarnpkg.com/en/docs/install)
* In the project directory, run `npm install` or `yarn install` depending on which you have
* Then run `npm run dev` and open your browser to `http://localhost:8080` to start working on the project
* To build the project run `npm run build`

### Firebase Hosting
* Install Node.js (v8.9.4 or above)
* launch command prompt/terminal 
* ```cd documents```
* ```git clone https://github.coma/accelerateplus/accelerateplus```
* ```cd Vibranium```
* Install project dependencies: ```npm install or yarn```
* Install Firebase CLI: ```npm i -g firebase-tools```or  ```yarn global add firebase-tools```
* Create a new firebase project [here](https://console.firebase.google.com/)
* Login into Firebase CLI: ```firebase login```
* Type ```firebase init``` to create a firebase.json
* Copy the static files (JS,CSS, Assets folders,index.html file) into a newly created 'Y' or 'N' folder
* Add project from firebase console using ```firebase -add project-name```
* Publish ```firebase deploy```

## Improvements

* <s>Mobile site enhancements</s> ✔
* <s>Add tutorials page</s> ✔
* <s>Add projects showcase page</s> ✔
* <s>Progressive Web App support</s> ✔
* Push notifications support 📢

## Updating
Here is a git workflow for updating your fork (or downloaded copy) to the latest version:
```git
git remote add upstream https://github.com/accelerateplus/accelerateplus.git
git fetch upstream
git merge upstream/Vibranium
# resolve the merge conflicts in your editor
git add . -u
git commit -m 'Updated to the latest version'
```
