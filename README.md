# Database-in-SQLite

## Description
An example program to create a database in SQLite to manage a bookstore which can easily be adapted to any other stockkeeping scenario.

## Table of Contents
1. Installation
1. Usage
1. Credits

## Installation
The code can be copied into any code editor.
Comments are available in the code to explain how each section works.

## Usage
As the program starts the user will be provided with the following menu from where they can choose to view different sections of the program.

![menu](https://user-images.githubusercontent.com/125367266/226485106-2ebfc72e-ea9e-4d93-be4c-64789271a0a9.JPG)

This gives the user access to:
* Enter a new book
    * The user is asked for a book ID, name, author and quantity.
    * If the user enters an ID that already exists or is not a number, an error message will be printed out and the user will be prompted to retry.
    * If the user was successful the book will be added to the database.
    
![add](https://user-images.githubusercontent.com/125367266/226485129-1d7aaee1-a353-44a8-a7c1-b3ab300f6fc6.JPG)

* Update an existing book
   * The user is presented with another menu.
   
   ![update menu](https://user-images.githubusercontent.com/125367266/226485167-c8aaffef-ef29-4baf-8227-f4f6c821a3e8.JPG)

   * Here they can decide if they want to update the title, author or quantity.
   * They are asked for the ID of the book they want to update. If the ID exists, they are asked for the new information and the book is updated.

* Delete a book
   * The users are asked to provide an ID of the book they want to delete.
   * If the ID is found the book will be deleted and a conformation message is printed.

![delete](https://user-images.githubusercontent.com/125367266/226485294-e6bead39-69df-4863-ad78-8778e6858e60.JPG)

* Search for a book
    * The user is asked for the ID of the book they want to look up.
    * If the book is found the entry is printed out.
    * If the book is not found an appropriate error message is printed out.
    
![search](https://user-images.githubusercontent.com/125367266/226485307-44495d3d-244d-4432-80c4-d364bc1b062b.JPG)

## Credits
This project was created by Christopher Barnard (ChrisTheFish96).
