## On Deck Coding Challenge

Hello! In this repository is my submission to the On Deck Coding Challenge.

This repository contains the code for an application that allows users to search for a city and get the weather from the city. It uses a React frontend and a Node Backend.

If the current temperature is less than or equal to 0 degrees Celsius in the chosen city then the land in the UI will turn white to indicate snow and otherwise will be green to represent grassland.

This project also implements browser storage for cities so the user is able save their selected city for the next browsing session. 

The project also features unit tests and is also deployed to a live URL: https://on-deck-coding-challenge.herokuapp.com

## Start the Application

To start the application first clone the repository to a working directory using git. Once the project is cloned, navigate to the directory called weatherappbackend.


After this open a terminal or command prompt window in your current directory and run the commands below.

```
npm install

node .
```

Once the previous command is completed, the server should become live after this open a new terminal or command prompt window and navigate to the directory calledweatherappfrontend in the directory where you cloned the project.

After this run the command below to start the front end.

```
npm install

npm start
```

If you would like to run the tests you can do so by running the command below in the weatherappfrontend directory

```
npm test
```
