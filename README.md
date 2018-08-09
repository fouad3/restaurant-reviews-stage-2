# Project : restaurant-reviews-stage-2
## By  Fouad Asharf

## Table of contents
- [Description](#description)
- [Project Folder Structure](#project-folder-structure)
- [Required Libraries and Dependencies](#required-libraries-and-dependencies)
- [How to Run Project](#how-to-run-project)
- [Copyright and license](#copyright-and-license)

## Description
took the responsive, accessible design built in [Stage One](https://github.com/fouad3/restaurant-reviews-stage-1) and connected it to an [external server](https://github.com/udacity/mws-restaurant-stage-2). used asynchronous JavaScript through fetch() API to request JSON data from the server. stored the data received from the server in an offline database using IndexedDB, which will create an app shell architecture. Finally, used Gulp build tool to automate time-consuming tasks in  development workflow, optimize the site to meet performance benchmarks and automate the process of converting the development code into streamlined production-ready code, this project is a part of the Udacity's[Mobile Web Specialist
Nanodegree](https://www.udacity.com/course/mobile-web-specialist-nanodegree--nd024).


## Project Folder Structure
    .
    ├── dist                    # distribution files for production
    ├── app                     # client-side files 
    ├── server                  # server-side files 
    └── README.md


## Required Libraries and Dependencies
  * [Node.js](https://nodejs.org/en/)
  * [Gulp.js](https://github.com/gulpjs/gulp/blob/master/docs/getting-started/1-quick-start.md)

## How to Run Project

1. clone or download this repository.

2. run the development local API server by using the following commands:
      1. Navigate to the server folder:
          ```
          cd restaurant-reviews-stage-2/server
          ```
      2. Install server dependancies:
          ```
          npm i
          ```
      3. Install Sails.js globally:
          ```
          npm i sails -g
          ```
      4. Start the server:
          ```
          node server
          ```
      
3. run the app by using the following commands:
      1. Navigate to the project folder:
          ```
          cd restaurant-reviews-stage-2
          ```
      2. Install app dependancies:
          ```
          npm i
          ```
      3. Start the app:
          ```
          gulp
          ```
      
 4. prepare the app for production by using the following commands:
 .
      1. Navigate to the project folder:
          ```
          cd restaurant-reviews-stage-2
          ```
      2. Start the production process:
          ```
          gulp build
          ```


## Attribution
* [Map Box API](https://www.mapbox.com/install/)
* [leafletjs](https://leafletjs.com/)
* [WICG/focus-visible](https://github.com/WICG/focus-visible)
* [Server-Side Code Owners](https://github.com/udacity/mws-restaurant-stage-2/blob/master/CODEOWNERS)

## Copyright and License
- supplied without rights information contributed by [Udacity](http://www.udacity.com).
