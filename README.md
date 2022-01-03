# unit-2-project

Technologies Used: IntelliJ, ERD Tool, Spring Boot,Maven,postgres,pgAdmin, Postman 

Project description: Created REST Api for database of a book website. The REST API will allow the User to keep track of their Books, Genres, Authors, and  Publishers.

Endpoints: 

Request Type:



(Books)
GET/API/books, Url: "/book", 

POST /api/books/1, Url: "books/1"

PUT /api/books/1, Url: "books/1"

DELETE /api/books/1, Url: "books/1"

GET /api/books/1/authors, Url: "books/1/authors"

POST /api/books/1/authors/1, Url: "books/1/authors/1"

(Genres) 
GET api/books/1/genres, Url: "books/1/genres"

POST api/books/1/genres/1, Url: "books/1/genres/1"

PUT api/books/1/genres/1, Url: "books/1/genres/1"

DELETE api/books/1/genres/1, Url: "books/1/genres/1"






(Publishers)
GET /api/books/1/publishers,  Url: "books/1/publishers"

POST /api/books/1/publishers, Url: "books/1/publishers"

PUT api/books/1/publishers/1, Url: "books/1/publishers/1"

DELETE api/books/1/publishers/1, Url:"books/1/publishers"






(Authors)
POST /api/books/1/authors/1,  Url:"books/1/publishers"

PUT /api/books/1/authors/1, Url: "books/1/authors/1"

DELETE /api/books/1/authors/1, Url: "books/1/authors/1"



User Stories


[Book Model]
As a user, I should be able to create new search catalog for a book.
As a user, I should be able to read the book.
As a user, I should be able to update the book.
As a user, I should be able to delete a book.




[Genre Model]
As a user, I should be able to create new search a genre.
As a user, I should be able to read a genre.
As a user, I should be able to update a genre.
As a user, I should be able to delete a genre.




[Author Model]
As a user, I should be able to create new search catalog for the author.
As a user, I should be able to read who is the author.
As a user, I should be able to update catalog of author.
As a user, I should be able to delete the current author in the catalog.




[Publisher Model]
As a user, I should be able to create a new search catalog for the publisher.
As a user, I should be able to read who is the publisher
As a user, I should be able to update catalog of publisher.
As a user, I should be able to delete the current publisher in the catalog.


Timeline 
Day 1 - Use Maven to download and build all of the dependencies, set up Spring Boot, set up dev environment, etc.
