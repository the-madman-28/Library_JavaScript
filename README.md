# Library Management System

This is a simple library management system web application built using HTML, Bootstrap, and JavaScript. Users can add books to the library by providing details such as the book's name, author, and type. The added books are displayed in a table, and the user interface is designed using Bootstrap for a clean and responsive layout.

## Table of Contents

- [HTML Structure](#html-structure)
- [JavaScript Logic](#javascript-logic)
- [Usage](#usage)
- [Running the Application](#running-the-application)

## HTML Structure

The `library.html` file contains the HTML structure of the application. It includes Bootstrap for styling and the necessary form elements for users to input book details. The added books are displayed in a table below the form.

## JavaScript Logic

The logic for the library management system is implemented in the `library.js` file. It includes a `Book` constructor to create book objects and a `Display` constructor to handle the display of books on the UI. The `Display` prototype contains methods to add books to the UI and clear the input fields after submission.

## Usage

To use the library management system, enter the details of the book (name, author, and type) in the provided form. Select the type of the book using radio buttons. Click the "Submit" button to add the book to the library. The added books will be displayed in the table below.

## Running the Application

1. Clone this repository.

```bash
git clone https://github.com/your-username/library-management-system.git
cd library-management-system
```
2. Open the 'library.html' file in a web browser.

3. Interact with the application by adding books through the provided form.
