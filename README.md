# Thursday-repetition


Since I will not be present this Thursday we can use this day to repeat some of the concepts covered so far. 

I will give you three coding exercises where the finished solutions are already present in this repo.

The goal of the exercise is to practice trying to write the code yourself in order to challenge your own understanding. 
Since the only goal here is to practice writing code already covered you do not have to deviate from the solution already present.
Start by cloning the repo for the exercise and use it as a cheat sheet along the way. To get the most out of the exercise however I encourage you to try writing as much as the code you can without just copy pasting code from the finished solution into your own.

As mentioned throughout the course the best approach when developing an application is to write code in very small steps and testing your application in every step. 
By only adding small pieces of code and testing your changes as often as possible you avoid getting stuck with a broken application with no idea of what code actually broke it. 

## Exercise 1.

project-3 from the react repository. 

Create a react application that uses the library: react-router-dom in order to add navigation to your application.

Repo: https://github.com/morsning/react.git

The project we want to replicate from within this repo is the one in folder: project-3

* Step 1.
Clone the finished solution/repo to some folder on your machine: 
git clone https://github.com/morsning/react.git
* Step 2. 
Go to the folder : project-3 of the cloned repo, right click in the folder and choose: git bash here
* Step 3. 
In the Git bash just opened type the following and press enter: npm install
(This will install all the dependencies of the project according to the list present in the projects package.json file)
* Step 4. 
In the same Git bash just opened type the following and press enter: npm start
* Step 5
The command above will stat a dev server and open a new browser or browser-tab where you through the address: localhost:3000 can view the finished solution. 
If a browser did not open just open a browser of your choice and navigate to: localhost:3000
* step 6
When you have a working copy of this project it is time to try to replicate this project by writing your own code. Create a new folder somewhere on your machine and create a new project from scratch by running the create react app command: 
create-react-app <nameOfYourProject>
* step 7
As we have done before start by opening this new project in your editor and remove all the files from the src directory. 
* Step 8 
Create a Index.js file in the Scr directory and start there. 

Remember to install all external modules you are importing into your files through: 
npm install <package>
for example:
If you are importing and using axios in any of your files thorugh: 
import axios from ‘axios’
you need to install this dependency from your git bash: 
npm install axios

Remember you can always copy paste from the finished solution you cloned if you get stuck.

Good luck. 


If you are finished early with exercise 1 you can move on to exercise 2 and 3

## Exercise 2

Repo: https://github.com/morsning/nodejs-express-react.git

Exact folder: react-get-from-api

Through this exercise we want to practice our understanding of separating our application into a back-end and front-end communicating through an API

The same process as described in exercise1. 
However since this exercise consists of both a front-end (React) and a back-end(Express) we need to start two servers in order to get this example working. 
We need to run: npm install in both the folders to install dependencies.
In the React folder we run: npm start
In the Express folder we start the server through the command: node app.js

## Exercise 3

This exercise is almost identical to exercise 2, however in addition to getting data from the server through a get request we are posting data to the server through a post request. In addition to just replicating this project you can try adding a couple of additional endpoints to your express application, and using these endpoints to post or get data from your React application. 

Repo: https://github.com/morsning/nodejs-express-react.git

Exact folder: react-post-to-api
