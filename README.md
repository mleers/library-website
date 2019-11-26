Project inspired by MDN Node express tutorial

This project features a fully working CRUD website connected to a database complete with dynamic views.  It demonstrates the following concepts and tools below:


###Concepts exercised in this project:
* MVC (Model View Controller pattern of development)
* HTML CRUD functionality
* Deployment considerations (route compression, vulnerability protection)
* Connecting/interfacing with an external databse

###Tools used:
* Node/express generator
* Pug view engine, bootsrap
* MongoDB NoSQL database, Mongoose ODM
* Hosted on Heroku


###How to make an entry: 
* Click "Create an author"
* Click "Create new genre" if there aren't any that apply yet
* Click "Create new book" to make the book itself
* Click "Create new book instance (copy)" to fill book status, editions etc.

###Routes Supported:
* `catalog/` home
* `catalog/<objects>/` READ list of objects
* `catalog/<object>/<id>` READ specific objects, id assigned server-side
* `catalog/<object>/create` CREATE 
* `catalog/<object>/update` UPDATE
* `catalog/<object>/delete` DELETE 


Live link showcasing this project: [https://evening-sea-52691.herokuapp.com/catalog]

