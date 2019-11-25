Project inspired by MDN Node express tutorial

Concepts exercised in this project:
* MVC (Model View Controller pattern of development)
* HTML CRUD functionality
* Deployment considerations (route compression, vulnerability protection)
* Connecting/interfacing with an external databse

Tools used:
* Node/express generator
* Pug view engine, bootsrap
* MongoDB NoSQL database, Mongoose ODM


How to operate:
* Create an author
* Select "Create new book" using the author just created
* Create new book instance to allocate a copy to the library

Routes Supported:
* `catalog/` home
* `catalog/<objects>/` READ list of objects
* `catalog/<object>/<id>` READ specific objects, id assigned server-side
* `catalog/<object>/create` CREATE 
* `catalog/<object>/update` UPDATE
* `catalog/<object>/delete` DELETE 


Live link showcasing this project: 

