# GoRestapi

Followed [Golang REST API With Mux](https://www.youtube.com/watch?v=SonwZ6MF5BE "Golang REST API With Mux") tutorial to implement my first REST API backend written in [GO](https://golang.org/ "GO Lang")

### Install mux router before run this application
```BASH
$ go get -u github.com/gorilla/mux
```

### Run this app in `terminal` with
```BASH
$ go run main.go
```

### Or build 'n run it with
```BASH
$ go build main.go
$ ./main
```

### Endpoints at `http://localhost:8000/api`
* `GET /books` get all books
* `GET /books/{id}` get single book
* `DELETE /books/{id}`
* `POST /books` create a new book
  ```
    # Request sample
    # {
    #   "isbn":"4545454",
    #   "title":"Book Three",
    #   "author":{"firstname":"Harry",  "lastname":"White"}
    # }
  ```

* `PUT /books/[id]` update a book
  ```
    # Request sample
    # {
    #   "isbn":"4545454",
    #   "title":"Updated Title",
    #   "author":{"firstname":"Harry",  "lastname":"White"}
    # }
  ```
