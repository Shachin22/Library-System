# Library Checkout System
## Overview
Library Checkout System using Python GUI and SQL database

## Project Structure

### menu
Main script that creates and runs the GUI aswell as incorporating all the individual modules.

### database
Has to be run to initialize the SQL database, and this database is then populated using a text file. This module also helps create columns to determine the status of a book such as if the book is reserved or if its unavailble.

### book search
Contains the functions to allow users to search for books based on the book title or book ID.

### book return
Contains the functions that determine if a book is able to be returned. Also updates the databases when a book is returned such that it is now available for other users to checkout the book.

### book checkout
Contains the functions that determine if a book can be checkout out such as validating user id and book id. Also updates the database that a book has been checked out and changes its status so that other users can instead reserve the book.
