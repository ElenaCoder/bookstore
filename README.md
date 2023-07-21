🔔 🔔 🔔
---
## About the project

This is the **bookstore** project, created as part of the "Metropolia UAS REACT.JS FUNDAMENTALS' course. The project aims to introduce the fundamental concepts of React.js and provide hands-on experience with building a React application.


## Task description

Create the Firebase project that is called bookstore. Create realtime database and import the following data. You can copy the data into the json file and import that.

```
{
"books" : {
  "-MGvq69vFRNAi6N4RPPf" : {
    "title" : "Anna Karenina",
    "author" : "Leo Tolstoy",
    "year" : "1877",
    "isbn" : "9780140864854",
    "price" : "13.5"
  },
  "-MGvqCptPhR1BMdNN2IQ" : {
    "title" : "The Haunting of Hill House",
    "author" : "Shirley Jackson",
    "year" : "1992",
    "isbn" : "9780141191447",
    "price" : "9.75"
  }
 }
}

```

Create front end to your Firebase bookstore realtime database REST API. The user should be able to list all books (with sort and filtering), add new books and delete existing books.

The defaut view.

![UI example:](./public/bookstore-ui-screenshot.jpg)



## Installation

1.Clone the repository or download the source code.

`git clone https://github.com/ElenaCoder/bookstore`

2.Install the dependencies.

`cd bookstore`

`npm install`


## Usage

1.Start the development server.

`npm start`

2.Open your web browser and navigate to http://localhost:3000 to view the React application.

## Deployment

This project is deployed and can be accessed at [this link:](https://elenacoder.github.io/bookstore/)

The deployment is done using GitHub Pages, which provides free hosting for static websites.

## Firebase Database Access Expiry

Please note that access to the Firebase database used in this project is set to expire on 2033-07-15. After this date, the database will no longer be accessible, and all associated data interactions will cease to function.

## Project Structure
```
├── public
│   ├── index.html
├── src
│   ├── App.js
│   ├── App.css
│   ├── AddBook.js
│   └── ...
│   ├── index.js
│   └── ...
├── package.json
└── README.md
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.


---