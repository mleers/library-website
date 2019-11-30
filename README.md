Project inspired by MDN Node express tutorial

Live link showcasing this finished project: https://evening-sea-52691.herokuapp.com/catalog

This project features a fully working CRUD website connected to a database complete with dynamic views.  It demonstrates the following concepts and tools below:


### Concepts exercised in this project:
* MVC (Model View Controller pattern of development)
* HTML CRUD functionality
* Deployment considerations (route compression, vulnerability protection)
* Connecting/interfacing with an external databse

### Tools used:
* Node/express generator
* Pug view engine, bootsrap
* MongoDB NoSQL database, Mongoose ODM
* Hosted on Heroku


### How to make an entry: 
* Click "Create an author"
* Click "Create new genre" if there aren't any that apply yet
* Click "Create new book" to make the book itself
* Click "Create new book instance (copy)" to fill book status, editions etc.

### Routes Supported:
* `catalog/` home
* `catalog/<objects>/` READ list of objects
* `catalog/<object>/<id>` READ specific objects, id assigned server-side
* `catalog/<object>/create` CREATE 
* `catalog/<object>/update` UPDATE
* `catalog/<object>/delete` DELETE 

### Todo
* [ ] additional styling for views
* [ ] user auth
* [ ] autofill capabilities in forms 



## Visuals:

### Create
<details><summary>View screenshot</summary>

![Screen Shot 2019-11-25 at 4 57 13 PM](https://user-images.githubusercontent.com/29722295/69591153-abd3e580-0fa6-11ea-9050-665be12665b2.png)
</details>

### Read
<details><summary>View screenshot</summary>

![Screen Shot 2019-11-25 at 4 57 26 PM](https://user-images.githubusercontent.com/29722295/69887846-de7b2800-129d-11ea-8860-c4fef81c48e7.png)
</details>

### Update
<details><summary>View screenshot</summary>

![Screen Shot 2019-11-25 at 5 11 10 PM](https://user-images.githubusercontent.com/29722295/69591181-c6a65a00-0fa6-11ea-8d7d-f1b696b8b119.png)
</details>

### Delete
<details><summary>View screenshot</summary>

![Screen Shot 2019-11-25 at 5 09 51 PM](https://user-images.githubusercontent.com/29722295/69887893-fd79ba00-129d-11ea-9320-692b52b271ca.png)
</details>

