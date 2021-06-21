# Microservices Practice Project

## Instructions for making simple microservices using React

### Project setup

1. Make a directory for the project  
   `mkdir blog`
1. Initiate git to start version control  
   `git init`
1. Within the blog dir, create a React App called 'client'  
   `npx create-react-app client`
1. Within the blog dir, make a directory for the post service  
   `mkdir post`
1. Within posts dir, make a package.json file and install dependencies  
   `npm init -y`  
   `npm install express cors axios nodemon`
1. Within the blog dir, make a directory for the comments service  
   `mkdir comments`
1. Within comments dir, make a package.json file and install dependencies  
   `npm init -y`  
   `npm install express cors axios nodemon`

### Service Creation

#### Post Service

1. Within posts dir, make an index.js file  
   `touch index.js`
1. Require express  
   `const express = require('express');`
1. Instantiate express app  
   `const app = express();`
1. Map POST and GET request routes (see source file)
