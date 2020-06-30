-- The Web User Interface - Web-UI --

This web-UI for support to obtain the user's request
In this Web-UI we have 2 folder:
   1. Adjustable_grid
   2. The Web-socket.io and Connection DB

1. Adjustable_grid: This is the index of web-UI. In this folder include the index.html and the the gridgenerator.js
The gridgenerator.js used to generate the grid to support the selection regions
The index.html is the code to connect with socket.io, make and send the request to socket.io

2. The Web-socket.io and Connection DB 
In this folder we have:
-The config folder contains the source code to connect the DB 
-The index.js used as a server, that is the source code to listen, receive, and store the request to DB. 

How to run: 
 
* install nodejs
* Configure the information of parameter to connect  in file config/default.json
* npm intall
* npm start =>> the socket.io run
* run the index.html
