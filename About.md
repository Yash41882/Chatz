Backend - 
First we create the server.js File in Backend Folder. There we import the necessary files and setup express.
Then we create the api calls then instead of creating the same long api calls, we will use middleware for auth and then create separate authRoutes.js file to distinctly create the remaining api calls.
then instead of creating the callback functions in the same api calls we will create a separate folder named "controller" to handle the callback functions just by calling them in api call.

setup the MONGO_DB_URI in .env file to establish connection with DB.
We have created db folder for separate file in connect to mongodb. There import
the mongoose and connect to mongo db using async and await function.

create a folder named models in backend and create files that will act as model
 or user schema for the DB.