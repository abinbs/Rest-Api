# Restful-Api
# A Book Manager

### Simple RESTful API to create, read, update and delete books. No database implementation yet

##### Simple GO Lang REST API


## Quick Start


``` bash
# Install mux router
# mux implements a request router and dispacher
go get -u github.com/gorilla/mux

https://github.com/gorilla/mux
```

``` bash
# To compile and build the project
go build

# Execution pf the project
./go Rest_Api
```


``` bash
# Since no database is implemented, POSTMAN application is used
# Postman is a collaboration platform for API development

https://www.postman.com/
```

## Operations


### Structure/Sample Request
``` bash

# {
#   "isbn":"4545454",
#   "title":"Fundamentals of Golang",
#   "author":{"firstname":"Harry",  "lastname":"White"}
# }

```

### Get All Books
``` bash
GET api/books
```
### Get Single Book
``` bash
GET api/books/{id}
```

### Delete Book
``` bash
DELETE api/books/{id}
```

### Create Book
``` bash
POST api/books

```

### Update Book
``` bash
PUT api/books/{id}

```
