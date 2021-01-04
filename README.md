React JS installation:
1. Install Node js with npm
2. Install Visual Studio Code or Submlime
2. npm install -g npm
3. npx create-react-app todolist_project

To-Do App in react js code:
This is a simple To Do Appliction in react.In this application I have used React Components, React Forms, event handlers.

Steps:
1. Create UI for adding to do list:
2. On button add called event handlers for adding list of to do items.
3. Displayed to-do list items.
4. Edit to-do list items on change event handlers
5. Delete button add for removing items and add delete event handlers.

Commands install to Use Font Awesome:
$ npm i --save @fortawesome/fontawesome-svg-core
$ npm i --save @fortawesome/free-solid-svg-icons
$ npm i --save @fortawesome/react-fontawesome

Commands to install react-flip-move
$ npm i react-flip-move

Deploy Your projects on Github:
1.Go to https://github.com site and create New repository with name.
2.In package.json file on your folder add below line:
 "homepage": "http://poojakute21.github.io/React-to-do-app",
 "homepage" : "http://username.github.io/repository-name",
 
 In scrips section add below lines:
	"predeploy": "npm run build",
    "deploy": "gh-pages -d build",
	
3.In command prompt go to projects
git init
git remote add origin https://github.com/poojakute21/React-to-do-app
git remote set-url origin https://github.com/poojakute21/React-to-do-app

npm install gh-pages --save-dev
npm run deploy

Run homepage URL to check your deployed code:

4. Add Your code to git repository:
git status
git add .
git commit -m "adding code files to gir repository"
git push origin master
