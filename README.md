# TweetApplication
A Mern Stack simple appliaction


## Install Instructions

- npm install express mongoose passport passport-jwt jsonwebtoken body-parser bcryptjs validator
- npm install -D nodemon
- change
    "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
    }
  to
    "scripts": {
    "start": "node app.js",
    "server": "nodemon app.js"
    }
- Issue with TextEncoder, fixed with  var util= require('util');
                                      var encoder = new util.TextEncoder('utf-8');
- 
