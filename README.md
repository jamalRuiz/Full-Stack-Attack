# Full-Stack-Attack
Jamal - Express (Backend) and Deployment 

1) Open a Terminal

2) Navigate into your 
$ cd 

3) After navigating into your backend repo, we're going to need to install the following dependencies :

$ NPM init -y 
$ NPM i express dotenv
$ NPM i cors



$ TOUCH server.js app.js .env .gitignore










Victor - PSQL (Backend) 











Jorge - React (Frontend)

Necessary steps to creating a Frontend React App 

1) Open a terminal

2) Key into your desired directory that is going to hold your fullstack app.

3) Create a folder that is going to hold both frontend and backend repos. 

4) To create your react app (frontend), run this command in your terminal: 
 $ npx create react-app 'Name of Your App' 

5) After creating your react app, we're going to need to install the following dependencies (package.json): 

 * React-Router-Dom - React Router DOM is an npm package that enables us to implement dynamic routing in a web app. It allows you to display pages and allow users to navigate them. It is a fully-featured client and server-side routing library for React.

 * Axios - Axios is a popular library that is mainly used to send asynchronous HTTP requests to REST endpoints. It is used to perform CRUD operations.

To install these dependencies, run the following code: 
 $ npm i axios react-router-dom

6) Next we need to create a .env file that is going to hold our REACT_APP_API_URL. In order to create this file, we first need to ensure we are on the same level as our gitignore file. 
(forgot the code to check that we are on the same level as our gitignore)

After we have verified that, we run the following code: 
 $ touch .env

7) Now that we have the .env file, we add our api url inside of it in the following format: 
  REACT_APP_API_URL='whatever your url is'

8) The next step can be done in your terminal or inside of your VS-Code. We are going to make folder that will hold our future pages and component files. To make these folders in the terminal, we first cd into our src folder witht the following code: 
 $ cd src
Then we run: 
 $ mkdir Components
 $ mkdir Pages

From here youre free to start your react-app how you think it best. However below we have a few tips on where you might want to begin: 

* Think about your route planning and the flow of your components and pages. What components might require what props?

* Remember that the current use of our pages files are to render our corresponding components. 

* More tips to be added later *
