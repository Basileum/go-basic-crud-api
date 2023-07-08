# Basic CRUD API in Go (go-basic-crud-api)

Thanks to [Akhil Sharma](https://github.com/AkhilSharma90)

Code written following his training course available on freeCodeCamp.org : [Learn Go Programming by Building 11 Projects – Full Course](https://www.youtube.com/watch?v=jFfo23yIWac)

## Purpose of the project
This project goal is to cover CRUD operations for a movie collection. These operations are performed on a slice containing the movies.
- GET /movies : get all movies
- GET /movies/<id> : get the movie with the specified id
- POST /movies : add a new movie from the one specified on the body of the request
- PUT /movies/<id> : update the movie with the specified id
- DELETE /movies/<id> : delete the movie with the specified id

## Built with
We use here [gorilla/mux](https://github.com/gorilla/mux) HTTP router.

## Test of the routes
Perfomed with Postman
