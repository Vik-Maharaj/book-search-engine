# Vik's Book Search Engine

## Description

Avid readers need a way to find new books to add to their repirotire, so to make the process of finding new books, and adding them to a list for future use, this full stack app was concieved and created.

This simple to use app runs entirely in the browser, can be accessed from anywhere, and was created utilizing JavaScript, Node.js, Express.js, and MongoDB. Google Books API search engine built with a RESTful API, refactor it to be a GraphQL API built with Apollo Server, and also featuters the following features JWT, React Hooks, UseState, UseEffect, as well as the following functionality:

- When the user loads the page they are presented with the search engine with a menu of options Search for Books and Login/Signup and an input field to search for books and a submit button
- If a user enter a search term in the input field and click the submit button they are presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site
- If the user decides to click the Login/Signup menu option then modal appears on the screen with a toggle between the option to log in or sign up
- Once a user signs up Signup, they can enter username, an email address, and a password, and a signup button and they are signed in
- If the user has previously signed in, they are able to log in and presented with two inputs for an email address and a password and login button
- Once the user is logged in, they have options change to Search for Books, an option to see my saved books, and Logout
- If the user searches for and finds a book they are intetrested in, they can click on the Save button on a book and that book’s information is saved to their account
- When the user clicks on the option to view their saved books, they are presented with all of the books I have saved to my account, each featuring the book’s title, author, description, image, and a link to that book on the Google Books site and a button to remove a book from my account
- At that point the user can click on the Remove button on a book and that book is deleted from my saved books list

Here are a couple of screenshot examples of the app in use:

![Vik's Book Search Engine](client/src/assets/screenshot-01.png)

![Vik's Book Search Engine](client/src/assets/screenshot-02.png)

The deployed site can be found at https://vik-book-search-engine.herokuapp.com.


## Installation

To install this application on your computer, first clone the repo to your local machine. Then, you will need to install the node dependencies/modules which can be done by running the ```npm install``` command in your terminal/bash shell. 

## Usage

Once the dependencies are installed, to use the application, initialize the server with the following command, ```npm run start```, and it can then be opened locally (or accessed any time via the above deployed site url).

Use the search bar to input any subject, title, or author then click "Submit Search."
If you would like to save books to a list you can access later, then click "Login/Sign Up" in the top right corner.
After signing up or loggin in, there will no be a blue button at the bottom of each book that says, "Save this Book!."
Saved books will now be in your books list, which can be access by the "See Your Books" link in the top right corner by the "Logout" button.

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

![NODE.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)

![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)

![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)

![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)