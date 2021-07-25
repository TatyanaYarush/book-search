# book-search

![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)
![npm](https://img.shields.io/npm/v/npm?color=orange&logo=npm)
![GitHub language count](https://img.shields.io/github/languages/count/TatyanaYarush/book-search?color=green)
![GitHub last commit](https://img.shields.io/github/last-commit/TatyanaYarush/book-search?color=orange)

Click here to open site:

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://pure-temple-72383.herokuapp.com/)

 ## Table of Contents
- [Introduction](#introduction)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Screenshots](#screenshots)
- [Dependencies](#Dependencies)
- [Resource](#information_source-resource)
- [Author](#raising_hand-author)
- [Questions](#questions)

## Introduction
A Google Books API search engine built with a RESTful API, and refactor it to be a GraphQL API. Built with Apollo Server using the MERN stack, with a React front end, MongoDB database, and Node.js/Express.js. Where users can search for books and saved them in their accounts.

## User Story

```md
AS AN avid reader
I WANT to search for new books to read
SO THAT I can keep a list of books to purchase

```
## Acceptance Criteria

```md
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

## Screenshots
Login screen           |  Users
:-------------------------:|:-------------------------:
![login screen](https://user-images.githubusercontent.com/70031550/126906400-9ce9aa2e-ce35-4a90-ad2f-1d38261c60dc.JPG)  |  ![users](https://user-images.githubusercontent.com/70031550/126906412-2919d133-45d9-4a87-9963-6b452d1b7b54.JPG)

Search screen           |  Save books screen
:-------------------------:|:-------------------------:
![search screen](https://user-images.githubusercontent.com/70031550/126906407-df7ea3c4-66f0-41f7-bc80-129200c8cfd1.JPG)  |  ![save books screen](https://user-images.githubusercontent.com/70031550/126906411-291e4d53-0a1e-4cb7-ba88-4d653b98642a.JPG)


## Dependencies
Server           |  Client
:-------------------------:|:-------------------------:
![server](https://user-images.githubusercontent.com/70031550/126906380-603bcd7f-2c18-49cb-8039-f7c484cacbf6.JPG)  | ![client](https://user-images.githubusercontent.com/70031550/126906389-1e14fa68-7926-4ee3-bded-5c76683b01d9.JPG)


### :information_source: Resource 
- [Queries and Mutations](https://graphql.org/learn/queries/)
- [GraphQL Playground](https://www.apollographql.com/docs/apollo-server/testing/build-run-queries/#graphql-playground)
- [React Router](https://reactrouter.com/web/guides/quick-start)
- [JSON Web Tokens](https://jwt.io/introduction)
- [Authentication in GraphQL API](https://www.apollographql.com/docs/apollo-server/security/authentication/)
- [Git hooks](https://git-scm.com/book/en/v2/Customizing-Git-Git-Hooks)
- [Resolvers](https://www.apollographql.com/docs/tutorial/resolvers/)
- [Debugger JWT](https://jwt.io/)
- [Deploy with Heroku and MongoDB Atlas](https://carleton.bootcampcontent.com/carleton-university/carl-ott-fsf-pt-02-2021-u-c/blob/master/18-NoSQL/04-Important/MongoAtlas-Deploy.md)

## :raising_hand: Author 
Written by Tatyana Yarushin student in full stack web development in the Coding Bootcamp course at Carleton University

**I hope you found something interesting!** :scroll:

## Questions
:question: For any additional information or questions find me at:

 - Email: [tatyana.yarushin@gmail.com](mailto:tatyana.yarushin@gmail.com)
 
 - Github: [TatyanaYarush](https://github.com/TatyanaYarush)
