# Simple NodeJS REST API
<img src="https://upload.wikimedia.org/wikipedia/commons/d/d9/Node.js_logo.svg"
     alt="Markdown Monster icon"
     alt="" width="40%" height="30%"
     class="aligncenter"
     />
> Simple RESTful API to create, read, update and delete movies. No database implementation yet
## Quick Start

``` bash
#logical and easy way to get resources asynchronously over the network

npm i node-fetch

#Is a utility-belt library for JavaScript that provides support for the usual functional suspects (each, map, reduce, filter...) without extending any core JavaScript objects.

npm i underscore
```
## Endpoints
``` bash
#All of the endpoints were configured on index.js like /api/movies that is the reason on the movies.js were only with "/"
```

### METHOD: GET - Get All Movies
``` bash
GET /
```

### METHOD: POST - Add a movie
``` bash
POST /
#{
#    "title": "Toy Story",
#    "director": "Jhon Lasseter",
#    "year": "2004",
#    "rating": "9.7"
#}
```
### METHOD: GET - Get Single movie
``` bash
GET /{id}
```

### METHOD: DELETE - Delete Person
``` bash
DELETE /{id}
```

### METHOD: PUT - Update movie
``` bash
PUT /{id}
# Request sample
#    "title": "Toy Story",
#    "director": "Jhon Lasseter",
#    "year": "2004",
#    "rating": "9.7"
#} 
```
```
### License
This project is licensed under the MIT License