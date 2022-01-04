# unit-2-project

Technologies Used: IntelliJ, ERD Tool, Spring Boot,Maven,postgres,pgAdmin, Postman 

Project description: Created REST Api for database of a book website. The REST API will allow the User to keep track of their Books, Genres, Authors, and  Publishers.

Endpoints: 

Request Type:



(Books)
[GET] endpoint: "/api/book" - Get all Books - Request Type: None

[GET] endpoint: "/api//books/{bookId}" - Request Type: None *

[POST]  endpoint: "/api/books/1" - Creating a Single Book -  Request Body: book info

[PUT]  endpoint: "/api/books/1" - Updating Single Book - Request Body: book info

[DELETE] endpoint: "/api/books/1" - Delete Single Book - Request Body;  None




(Genres) 
[GET] endpoint: "/api/books/1/genres" - Get all Genres- Request Body: None 

[GET] endpoint: "/api//genres/{genreId}" - Request Type: None *

[POST]  endpoint: "/api/books/1/genres/1" - Create a Single Genre - Request Body: genre info

[PUT]  endpoint: "/api/books/1/genres/1" - Update a Single Genre - Request Body: genre info

[DELETE]  endpoint: "/api/books/1/genres/1" - Delete a Single Genre - Request Body : None




(Publishers)
[GET] endpoint: "/api/books/1/publishers" - Get all Publishers - Request Type: None

[GET] endpoint: "/api/publishers/{publisherId}" - Request Type: None *

[POST]endpoint: "/api/books/1/publishers" - Create a Single Publisher - Request Type: publisher info

[PUT] endpoint: "/api/books/1/publishers/1" - Update a Single Publisher - Request Type: publisher info

[DELETE] endpoint:"/api/books/1/publishers" - Delete a Single Publisher - Request Type: None



(Authors)



[GET] endpoint: "/api/authors/{authorId}" - Request Type: None *

[POST] endpoint: "/api/books/1/authors/1" - Get a Single Author - Request Type: author info

[PUT] endpoint: "/api/books/1/authors/1" - 	Update a Single Author - Request Type: author info

[DELETE] endpoint: "/api/books/1/authors/1" - Delete a Single Author



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
