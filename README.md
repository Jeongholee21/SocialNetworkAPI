# SocialNetworkAPI

## Description
A REST API for a social media app. Built with Express, Mongoose, and MongoDB.

## Build With
* MongoDB 
* Mongoose
* Express
* Node
* Nodemon

## VIDEO DEMO

1. https://drive.google.com/file/d/1VumJqr-Z5Nc2s9C-vVyYMcS2gf1JUy6E/view
![](Screenshots/1.gif)
2. https://drive.google.com/file/d/10WegrNLZ-I-HVcuLYEY70IVFlGWWYqZq/view
![](Screenshots/2.gif)

## USAGE 
This application allows you to navigate different link routes that display data from the database. 

- GET/ POST routes: <br>
    `http://localhost:3001/api/users` <br>
    `http://localhost:3001/api/thoughts`<br>

     - If you wish to <u>GET</u> a certain id you can do so by adding an `/id` at the end of the link. 

- PUT/DELETE routes: <br>
    `http://localhost:3001/api/users/:id`<br>
    `http://localhost:3001/api/thoughts/:id` <br>

- POST/ DELETE routes: <br>
    `http://localhost:3001/api/users/:id/friends/:friendId` <br>
    `http://localhost:3001/api/thoughts/:id/reactions` <br>