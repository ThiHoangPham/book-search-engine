<h1 align="center"> MERN - BOOK SEARCH ENGINE 🚩</h1>
<br>
<p align="center">
  <a href="#">
  <img alt="apollo server" src="https://img.shields.io/badge/-ApolloGraphQL-311C87?style=for-the-badge&logo=apollo-graphql" target="_blank" />
  <a href="#">
  <img alt="nodejs" src="https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white" target="_blank" />
  <a href="#">
  <img alt="graphql" src="https://img.shields.io/badge/-GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white" target="_blank" />
  <a href="#">
  <img alt="react" src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" target="_blank" />
  <a href="#">
  <img alt="mongodb" src="https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white" target="_blank" />
  <a href="#">
  <img alt="javascript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascriptlogoColor=black" target="_blank" />
  <a href="#">
  <img alt="css3" src="https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white" target="_blank" />
  <a href="#">
  <img alt="npm" src="https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white" target="_blank" />
  <a href="#">
  <img alt="heroku" src="https://img.shields.io/badge/heroku-%23430098.svg?style=for-the-badge&logo=heroku&logoColor=white" target="_blank" />
  <a href="#">
  <img alt="html5" src="https://img.shields.io/badge/HTML-239120?style=for-the-badge&logo=html5&logoColor=white" />
  <br>
  <a href="#">
  <img alt="watchers" src="https://img.shields.io/github/watchers/ThiHoangPham/book-search-engine?color=%2346b946&style=flat-square" target="_blank" />
  <a href="#">
  <img alt="rep size" src="https://img.shields.io/github/repo-size/ThiHoangPham/book-search-engine?style=flat-square" target="_blank" />
  <a href="https://github.com/ThiHoangPham/book-search-engine/blob/main/LICENSE">
  <img alt="License: Apache 2.0" src="https://img.shields.io/badge/license-APACHE-yellow.svg?style=flat-square" target="_blank" />
  </a>
  <a href="#">
  <img alt="fork" src="https://img.shields.io/github/forks/ThiHoangPham/book-search-engine.svg?style=flat-square" target="_blank" />
  <a href="#">
  <img alt="repo star" src="https://img.shields.io/github/stars/ThiHoangPham/book-search-engine?color=%23ff00bf&style=flat-square" target="_blank" />
  </a>
  <a href="#">
  <img alt="contributors" src="https://img.shields.io/github/contributors/ThiHoangPham/book-search-engine?style=flat-square" target="_blank" />
  </a>
  <a href="#">
  <img alt="top language" src="https://img.shields.io/github/languages/top/ThiHoangPham/book-search-engine?color=%23ff4000&style=flat-square" target="_blank" />
  </a>
  <a href="#">
  <img alt="issue open" src="https://img.shields.io/github/issues-raw/ThiHoangPham/book-search-engine?style=flat-square" target="_blank" />
  </a>
</p>
<hr>

  <h3 align="center">
    <p align="center">
      <a href="https://github.com/ThiHoangPham/book-search-engine"><strong>Explore the docs »</strong></a>
      <br />
      <br />
      <a href="https://rocky-dusk-11270.herokuapp.com/">Demo</a>
      ·
      <a href="https://github.com/ThiHoangPham/book-search-engine/issues">Report Bug</a>
      ·
      <a href="https://github.com/ThiHoangPham/book-search-engine/issues">Request Feature</a>
    </p>
  </table>

  <details>
    <summary>Table of Contents</summary>
    <ul>
      <li><a href="#about-the-project">About The Project</a>
      <li><a href="#user-story">User Story</a></li>
      <li><a href="#acceptance-criteria">Acceptance Criteria</a></li>
      <li><a href="#live-demo-github">Live Demo Heroku</a></li>
      <li><a href="#installation">Installation</a></li>
      <li><a href="#usage">Usage</a></li>
      <li><a href="#contributor">Contributor</a></li>
      <li><a href="#contribution">Contribution</a></li>
      <li><a href="#license">License</a></li>
      <li><a href="#more-about-me">More About Me</a></li>
    </ul>
  </details>

  <br />

# About The Project
  A portfolio using your new React skills, which will help set you apart from other developers whose portfolios don’t use the latest technologies. This application is deployed to GitHub Pages.

  ![demo-portfolio-demo-gif](./client/src/book-search-engine.gif)

# User Story
```
AS AN avid reader
I WANT to search for new books to read
SO THAT I can keep a list of books to purchase
```

# Acceptance Criteria
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

# Live Demo Github: 
<a href="https://rocky-dusk-11270.herokuapp.com/">
  <img alt="live demo heroku" src="https://img.shields.io/badge/demo-heroku-%23430098.svg?style=for-the-badge&logo=heroku&logoColor=white" target="_blank" />
  </a>

# Installation
```
Clone/Fork the Repo to your Local, and run command:

`npm install`
```
# Usage
```
Run the following command at the root of your project:

`npm start`
```
# Contributor
<a href="https://github.com/ThiHoangPham/book-search-engine">
  <img alt="contributor" src="https://contrib.rocks/image?repo=ThiHoangPham/book-search-engine" target="_blank" />
  </a>

# Contribution
This how you can contribute to this project:
```
> Clone the project to your local 
> Create your own branch
> Add contribution codes/commit/push to remote repo
> Create a pull request
```
# License
  Distributed under the [Apache License 2.0](https://github.com/ThiHoangPham/book-search-engine/blob/main/LICENSE)

# More About Me
  <a href="https://github.com/ThiHoangPham">
  <img alt="profile-github" src="https://img.shields.io/badge/Profile-GitHub-100000?style=for-the-badge&logo=github&logoColor=white" target="_blank" />
  <a href="https://thihoangpham.github.io/react-portfolio/">
  <img alt="portfolio-page-latest" src="https://img.shields.io/badge/Portfolio-Page-FEAA2D?style=for-the-badge&logo=deezer&logoColor=white" target="_blank" />
  <a href="https://www.linkedin.com/in/thaihoangpham/">
  <img alt="portfolio-page-latest" src="https://img.shields.io/badge/Profile-LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank" />
  <a href="mailto:thaihoangpham2008@gmail.com">
  <img alt="email-adam" src="https://img.shields.io/badge/Email to me-Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" target="_blank" />
  </br>
  <p align ="right"><a href="#">↥ back to top</a></p>

- - -

© 2022 Hoang Thai Pham(Adam): MERN - Book Search Engine
