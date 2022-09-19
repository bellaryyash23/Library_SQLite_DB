# 📚Virtual Library Management usign SQLite and SQLAlchemy ORM of Python

🌟A Virtual Library Management Website which allows user to keep track of the books in their library and also to add rating to the book while being able to edit and delete it from the
program. The record of books is maintained using the SQLite Database and simple HTML is used to create the interface for the user to access the database.

🌟📚The Final Website with all the basic CRUD operations for library database management is as follows📚

![Final Website](https://github.com/bellaryyash23/Library_SQLite_DB/blob/master/samples/site.gif?raw=true)

👆Final Virtual Library Website👆

👉Here we have used both the SQLite operations and SQLAlchemy simplified operations to operate a database.

👉The 'database.py' file is used to perform the CRUD operations using SQLite. Since the operations are Case sensitive and prone to error, we use the ORM Object Relational Mapping
library SQLAlchemy provided by Python

👉In the 'main.py' file, the Flask app is setup for hosting the website on local server. Then the database is created for this application using the SQLAlchemy Flask extension.

👉Now, the home route of website is setup using the Flask decorator functions. On the home page of website all the books from the database are to be displayed. This is 
done using 'db.session.query(Book).all()' command to get all entry of books.

![Home Page of Website](https://github.com/bellaryyash23/Library_SQLite_DB/blob/master/samples/home.jpg?raw=true)

👆Home Page of Website👆

👉We can add new books to the database using the add option present on the home page where user can make entry of new book, author name & add rating to that book. This is
done using HTML forms and data creation operation of SQLAlchemy.

![Page to Add new Book to Website](https://github.com/bellaryyash23/Library_SQLite_DB/blob/master/samples/add.jpg?raw=true)

👆Add New Book to Database👆

👉For each book entry on the home page, we have the option to edit the rating of the book & the option to delete the book from our records. These operations of Updations
& Deletion are performed with help of SQLAlchemy commands and HTML Forms.

![Edit Rating of Book](https://github.com/bellaryyash23/Library_SQLite_DB/blob/master/samples/edit.jpg?raw=true)

👆Edit the Book rating👆

👉Finally the SQLite Database we have create can be viewed using the 'DBViewer' software, to visualize the structure of the database.

![Database of Website](https://github.com/bellaryyash23/Library_SQLite_DB/blob/master/samples/database.JPG?raw=true)

👆The Virtual Library SQLite Database👆
