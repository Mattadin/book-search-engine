# Book Search Engine

## Description

Book Search Engine allow you to search for and then save books.

It was a fully functioning Google Books API search engine built with a RESTful API that required refactoring to be a GraphQL API built with Apollo Server. The app was built using the MERN stack, with a React front end, MongoDB database, and Node.js/Express.js server and API.

## Table of Contents

- [Description](#description)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Installation](#installation)
- [Usage](#usage)
- [Tests](#tests)
- [Technology Used](#technology-used)

## User Story

```
AS AN avid reader
I WANT to search for new books to read
SO THAT I can keep a list of books to purchase
```

## Acceptance Criteria

```
GIVEN a book search engine
WHEN I load the search engine
THEN I am presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button
WHEN I click on the Search for Books menu option
THEN I am presented with an input field to search for books and a submit button
WHEN I am not logged in and enter a search term in the input field and click the submit button
THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site
WHEN I click on the Login/Signup menu option
THEN a modal appears on the screen with a toggle between the option to log in or sign up
WHEN the toggle is set to Signup
THEN I am presented with three inputs for a username, an email address, and a password, and a signup button
WHEN the toggle is set to Login
THEN I am presented with two inputs for an email address and a password and login button
WHEN I enter a valid email address and create a password and click on the signup button
THEN my user account is created and I am logged in to the site
WHEN I enter my account’s email address and password and click on the login button
THEN I the modal closes and I am logged in to the site
WHEN I am logged in to the site
THEN the menu options change to Search for Books, an option to see my saved books, and Logout
WHEN I am logged in and enter a search term in the input field and click the submit button
THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site and a button to save a book to my account
WHEN I click on the Save button on a book
THEN that book’s information is saved to my account
WHEN I click on the option to see my saved books
THEN I am presented with all of the books I have saved to my account, each featuring the book’s title, author, description, image, and a link to that book on the Google Books site and a button to remove a book from my account
WHEN I click on the Remove button on a book
THEN that book is deleted from my saved books list
WHEN I click on the Logout button
THEN I am logged out of the site and presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button
```

## Installation

To install this application, clone the code into your terminal for the respective repository. Then, install npm by entering the command `npm install` into the root directory of the terminal. This will install all dependencies in the `package.json` required to run this application. Don't forget to add `.gitignore` files to include node_modules before installing npm.

## Usage

Run the following commands in the command-line in the root of the folder

1. npm install
2. npm run build
3. npm run develop
4. The browser will open at http://localhost:3000/
5. Sign Up for an account by entering an email, username, and password
6. After signing up, you will automatically be logged in
7. Once logged in, you may search for a book
8. You have the ability to save books, which you can retrieve at the "See Your Books" tab
9. You can search for books again using the "Search For Books" tab
10. You may logout by hitting the "logout" button

## Tests

![GitHub license](https://img.shields.io/badge/test-100%25-success)

## Technology Used

• React
• Bootstrap
• Node.js
• Express.js
• HTML
• CSS
• Javascript
• JSX
• Apollo Server
• Graph QL
• MongoDb
• Mongoose
• Heroku
