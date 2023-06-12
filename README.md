# HABIT TRACKER APPLICATION
> A simple habit tracking app based on NodeJS + EJS for user habit management on daily and weekly basis. 


## Tech-Stack
* HTML, CSS (for frontend interface)
* Javascript, EJS 
* NodeJS and expressJS (for backend server)
* MongoDB (as database to store habits and users)


## Usage Guide
1. Install [nodejs](https://nodejs.org/en/) and [MongoDB](https://www.mongodb.com/) on your system.
2. Open your terminal and run the following :
    ```
    cd HABIT
    npm install
    npm start
    ```
3. Now the Server runnning, open the link (http://localhost:3000) to acess the interface.

## Folder Structure
* app.js - Entry point of our application. This file defines our express server.
* assets - This folder contains static files like styles(css),svg.
* config - This folder contains configuration of Mongoose(schema and model)
* models - This folder contains schema definition of our mongoose models.
* routes - This folder contains all the routes for our API.
* views - This folder contains layout, partials and templates to be displayed to the user.
