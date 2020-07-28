# BudgeTrac
Budget Tracker App

## Table of contents
--------------------
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)
* [Testing](#testing)
* [Features](#features)

## General info
--------------------
This project was created as an exercise practicing creating an PWA for a budget tracker app using Service Workers, Installable Manifest, IndexedDB, and several other quality of life packages.
	
## Technologies
--------------------
Project is created with:
* compression: ^1.7.4,
* express: ^4.17.1,
* morgan: ^1.10.0,
* mongoose: ^5.9.25
	
## Setup
--------------------
### install the following locally using npm:
```
$ cd ../dir
$ npm init
$ npm install express
$ npm install morgan
$ npm install mongoose
$ npm install compression
```

## Testing
--------------------
### To test this project, run the following in the terminal:
```
$ npm start
```
The server should run on PORT 3001
--------------------
Alternatively, you can find the app deployed on [Heroku](https://guarded-gorge-18618.herokuapp.com/)

## Features
--------------------
### Features include:
* ADD EXPENSE OR DEPOSIT INPUTS
* INPUTS PERSIST WHEN OFFLINE AND ADD TO DB WHEN RECONNECTED TO INTERNET
* ABILITY TO INSTALL APP ON DESKTOP/HOMESCREEN AS APP