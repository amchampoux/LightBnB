# lighthouseBnb

A database application project developed as a part of Lighthouse Labs Web development course. The front-end is forked from lighthouse-labs/LightBnB_WebApp. The goal was to design a database and use server-side JavaScript to display the information from queries to web pages by applying knowledge of complex SQL queries, database and ERD (entity relationship diagram) design to integrate the database with a Node backend.


## Core Features
- Users can browse for properties to rent and use search filters to refine the properties list
- Once logged in, the can see their properties and reservations
- Users can create a new property listing
- New users can create an account

## Screenshots

**Home page**

!["Screenshot of the Homepage](https://github.com/amchampoux/LightBnB/blob/main/docs/index.png)

**Login**

!["Screenshot of the Login page](https://github.com/amchampoux/LightBnB/blob/main/docs/login.png)

**My reservations**

!["Screenshot of the My reservations page](https://github.com/amchampoux/LightBnB/blob/main/docs/my_reservations.png)

**Search**

!["Screenshot of the Search form](https://github.com/amchampoux/LightBnB/blob/main/docs/search.png)

## ERD

**Diagram**

!["Diagram"](https://github.com/amchampoux/LightBnB/blob/main/docs/erd.png)

## Getting Started
1. Install the LightBnB_WebApp and dependencies using the `npm install` command.
2. Start the web server using the `npm run local` command. 
3. The app will be served at <http://localhost:3000/>.
4. Go to <http://localhost:3000/> in your browser and browse properties
5. You can login using the test user tristanjacobs@gmail.com / password

## Dependencies
- Express
- Node 5.10.x or above
- nodemon
- bcrypt
- body-parser
- cookie-session
- Node-postgres





