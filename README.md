# Vik's Book Search Engine

## Description

Avid readers need a way to find new books to add to their repertoire, so to make the process of finding new books and adding them to a list for future use easier, this full stack app was conceived and created.

This simple to use app runs entirely in the browser, can be accessed from anywhere, and was created utilizing JavaScript, React.js, Node.js, Express.js, and MongoDB. The Google Books API search engine was called and refactored to be a GraphQL API built with an Apollo Server. And the app also included the use of these features: JWT, React Hooks, UseState, and UseEffect, as well as the following functionality:

- When the user loads the page, they are presented with the search engine with a menu of options “Search for Books” and “Login/Signup”, as well as an input field to search for books and a submit button
- If a user enters a search term in the input field and clicks the submit button, they are presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site
- If the user decides to click the “Login/Signup” menu option then a modal appears on the screen with a toggle between the option to log in or sign up
- Once a user signs up, they can enter a username, an email address, and a password — and they are then signed in
- If the user has previously signed in, they are able to log in and are then presented with two inputs for an email address and a password
- Once the user is logged in, their options change to “Search for Books”, an option to see “My saved Books”, and “Logout”
- If the user searches for and finds a book they are interested in, they can click on the Save button on a book and that book’s information is saved to their profile
- When the user clicks on the option to view their saved books, they are presented with all of the books they have saved, each featuring the book’s title, author, description, image, and a link to that book on the Google Books site
- At that point the user can click on the “Delete this Book” button on a book and that book is removed from their saved books list


Here are a couple of screenshot examples of the app:

![Vik's Book Search Engine](client/src/assets/screenshot-01.png)

![Vik's Book Search Engine](client/src/assets/screenshot-02.png)

The deployed site can be found at https://vik-book-search-engine.herokuapp.com.


## Installation

To install this application on your computer, first clone the repo to your local machine. Then, you will need to install the node dependencies/modules which can be done by running the ```npm install``` command in your terminal/bash shell. 

## Usage

Once the dependencies are installed, to use the application, initialize the build with the command ```npm run build```, and once that operation is complete, start the server with the following command, ```npm run start``` — the app can then be opened locally (or accessed any time via the above deployed site url).


## Credits

Collaborators include the instructor, TAs, and fellow classmates of the UCF Coding Bootcamp (Spring 2022).


## License

Copyright (c) 2022 Vik Maharaj

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


## Badges

![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)

![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)

![NODE.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)

![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)

![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)

![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

![Apollo-GraphQL](https://img.shields.io/badge/-ApolloGraphQL-311C87?style=for-the-badge&logo=apollo-graphql)

![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)

![NPM](https://img.shields.io/badge/NPM-%23000000.svg?style=for-the-badge&logo=npm&logoColor=white)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)