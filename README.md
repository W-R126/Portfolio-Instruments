# Portfolio Instruments

Portfolio Instruments is a full-stack website built with all the tools needed to manage your passive investment portfolio.  

Portfolio Instruments is useful for both beginner and advanced investors.  Portfolio Instruments will take snapshots of your portfolio at various points in time and provide rebalance guidelines based on user-defined criteria.  

Portfolio Instruments provides strong benchmark portfolios from which to reference so that users of all backgrounds have an easy way to manage their money.  Portfolio Instruments provides an intuitive dashboard display that shows all the information that one might require as a passive investor.


## Motivation

For a large part of my early adult life, I spent a great deal of time reading about effective passive investing strategies.  I have been an avid investor since I first began working, and I continue to believe that a solid passive investing strategy can greatly reduce the financial stress in ones life by providing great stability.  

Throughout my adult life, I have found myself repeating certain investing rebalance calculations which have become very tedious.  This website was built to automate and intuitively display much of this information required to analyze your passive portfolio.  

Many newcomers are usually unsure of how to begin investing.  This website also aims to reduce the stress of passive investing for the new investor by breaking down strong benchmark portfolios that have been pre-chosen based on stability and popularity.


## Website Breakdown

### Main Features

*  Dashboard - Features graphs and charts breaking down the most recent snapshot of your portfolio.  Shows a graph of your net worth, charts with information on your asset breakdown by percentages, and analysis of your holdings by tax space and financial institution.

*  Portfolio Benchmarks - Provides a list of strong portfolio references with which to model your own portfolio.  Provides information on historical risk and return to help equip the user with the information needed to choose a personal portfolio.

*  Snapshots - Add a current snapshot of your portfolio for tracking and analysis.  This snapshot will combine with your user preferences to figure out if any rebalancing is necessary and suggest next actions as applicable.

### Secondary Features

* Login - User data is safely segregated by encyrpted login.

* User Preferences - User preferences will be set upon login and will help the website decide how to suggest certain actions such as rebalancing.

* Snapshot History - Provides the user with net worth tracking and a history of submitted snapshots of the user's portfolio at any given time.


## Code Structure

* Database: PostgreSQL database migrated and queried using Sequelize.js

* Server Routes: Set up using Express.js & Node.js

* Front-End: Built using React.js & Redux.js; found in the client/src folders

If pulling from GitHub, make sure to run an npm install at both the highest level and the client level.  An easy way to run the program would be to run a nodemon on app.js and to run an npm start in the client folder.


## Database Structure

1.  Users Table
2.  Snapshots Table
3.  Accounts Table
4.  Stocks Table
5.  Fixed Income Table
6.  Real Assets Table

![Database Breakdown](/images/PI_Database.png)


## React States, Actions, & Reducers




## How to Use

The website is not fully functional yet and is still not ready for normal use.  If hosting is currently available, you can test out the latest features by logging in [here](www.portfolioinstruments.com) using the following credentials - 

Username: Matt ,
Password: password

This section will be updated when all major features have been successfully added.


## YouTube Demo

A video of the current features are shown [here](https://www.youtube.com/watch?v=A9sfTssVGz8).





## Completed Features

* Secure Login
* Dashboard minus the Net Worth Graph
* Add Snapshot tables to front-end and database
* Select from a host of portfolio benchmarks

All features are based on a full-stack, meaning all requirements were fulfilled by using a back-end server and database while maintaining dynamic states on the React front-end.


## In-progress Features

* Customizable user configuration settings
* Net worth graph
* Breakdown of all user snapshots
* Live rebalance analysis


## Challenges

I want to open by saying that this is a major coding project for just one person.  This project features the use of many nested tables that are difficult to query.  It features a complicated React front-end which has 25+ components.  It features a complicated segregation and format of assets that must dynamically display on both the front-end and secure itself into our back-end database.

Due to the above, time is a huge constraint, and debugging in the context of such a large codebase can become very difficult. Juggling this project along with other class projects was extremely time consuming and challenging. 

Managing states with React is also difficult if not properly architected and mapped out ahead of time due to the increasing scale of the project.

Proper data formatting on both the front and back-end proved especially challenging.

Many of these technologies are new to me, and so I am learning best practices, do's, and don'ts as I go.


# Technologies

HTML, CSS ,Bootstrap, JavaScript, Node.js, Express.js, React.js, Redux.js, ReduxThunk, PostgreSQL, Sequelize.js, Passport.js, Chart.js, Heroku, Surge

# Author
* [Matthew Fisher](https://github.com/MicroFish91)


# Special Thanks
* [Veronica Lino](https://github.com/vlino2015) - I could not have made it this far without you, thank you for being an amazing instructor!