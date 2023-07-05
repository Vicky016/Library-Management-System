# Library-Management-System

install MySql in your system, you can also refer yt video for that...
it is important to have MySql for this application

**create database for the project with the following command**
**VERY IMPORTANT STEP**
create database db;
use db;
create table books(bid varchar(20) primary key, title varchar(30), author varchar(30), status varchar(30));
create table books_issued(bid varchar(20) primary key, issuedto varchar(30));

desc books;
desc books_issued;


**Description of Project Files**
Below are the project files you will get once you download and extract the Library project:

main.py – which does function call to all other python files
AddBook.py – To add the book
viewBooks.py – To View the list of books in the library
DeleteBook.py – To Delete a book from library
IssueBook.py – To Issue a book from library
ReturnBook.py – To Return a book to the library
