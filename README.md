# NOTE TAKER -- HOMEWORK 11

## Description  
This is a simple web application that helps users stay organized. It allows them to write, save, and delete notes. 

## Table of Contents

* [Technologies Used](#technologies-used)

* [Libraries Used](#libraries-used)

* [Dev Dependencies](#dev-dependencies)

* [How to Use](#how-to-use)

* [How I Made This](#how-i-made-this)

* [Deployed Application](#link-to-deployed-application)

* [GitHub Repo](#link-to-github-repo)

* [Future Development Ideas](#future-development-ideas)

## Technologies Used  
Built in Visual Studio with        
HTML     
CSS    
Javascript      
Node.js    
Express     

## Libraries Used
Bootstrap    
Font Awesome    

## Dev Dependencies  
Express       
fs  
uuid      

## How to Use  
Navigate to (https://still-dusk-77371.herokuapp.com) and click the "Get Started" button. A new page will appear that will display any previously saved notes on the left side of the screen. Click on any of the saved notes to view their content. Click a note's trash icon to delete that note.  

If you would like to write a new note, click the pencil icon in the upper right corner of the page. Write your new note's title in the "Note Title" field and then write the body of your note in the "Note Text" field. Click the disc icon in the upper right corner of the screen to save your new note.

![image](https://media.giphy.com/media/WUaLBQzu1MQqyCE0qd/giphy.gif)

## How I Made This  
I was given a lot of starter code for this project: the html, css, and index.js files were already completed and did not need to be modified for this project. There was also a barebones package.json established and a db.json file as well with a mosty-empty object inside.

The first thing I did was install my dependencies. Then I got my server started in the server.js file. After that, I wrote two more files: one that handled the html routes and one that handled the api routes. 

Once this was all working, I tested it and deployed to Heroku.

This project allowed me to learn how to connect the front end and back end code for a full stack application. I learned how to use the delete method in my api routes, how to use uuid in order to generate unique ids for items in my database, and how to use middleware to serve a static resource. This is also the first real project I've deployed to Heroku, which was a headache at first and resulted in two hours of debugging, but it eventually worked.

## Link to Deployed Application
(https://still-dusk-77371.herokuapp.com)

## Link to GitHub Repo    
(https://github.com/alyssahellrung/Express-Note-Taker)

## Future Development Ideas
I would like to add unique styling and more functionality to this app (for instance, the ability to add photos and/or links to notes).
