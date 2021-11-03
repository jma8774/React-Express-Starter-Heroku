# Starter Pack for React and Express
A simple starter project with React frontend and Express backend that can be easily deployed onto Heroku.

## Heroku Deploy Instructions
1.  Clone this project as a new GitHub project
2.  Setup a Heroku app and connect the GitHub project to Heroku
3.  Click deploy and Heroku should be able to generate a website for it

## Test
Go to ``` https://<your-app-name>.herokuapp.com/ ``` and you should see ``` Hello World ```

Go to ``` https://<your-app-name>.herokuapp.com/user ``` and you should see the backend response ``` User home route ```

## Local Commands
### Initialize
Before you do anything, make sure you install all the dependencies in the ``` package.json ``` file locally in the root folder and in the server folder by doing
```
npm install 
```
and then ``` cd server ``` and
```
npm install 
```

### React
To start the React app, go to the root of the folder and run 
```
npm run dev
```
will launch the React client at http://localhost:3000/

### Express Node
To start the Express backend, from the root folder, ``` cd server ``` and then
```
npm run dev
```
will launch the Express backend at http://localhost:5000/
