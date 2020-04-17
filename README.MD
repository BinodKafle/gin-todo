# Api go simple
It is a just simple REST API with Go using:
1. **Gin Framework**
2. **Gorm** 

## Installation & Run
```bash
# Download this project
$ go get github.com/go-sql-driver/mysql

# Download Gin Framework
$ go get github.com/gin-gonic/gin

# Download GORM
$ go get github.com/jinzhu/gorm
```

## DB Setup
1. Go to Config/Database.go
2. Update DBName, User, Password and Host, Port according to your database configuration

## API list

* `GET` : `v1/todo` Get all todos
* `POST` : `v1/todo` Create a todo
* `GET` : `v1/todo/{id}` Get a todo
* `PUT` : `v1/todo/{id}` Update a todo
* `DELETE` : `v1/todo/{id}` Delete a todo

## Post Params
```
{
	"name": "Groceries shopping",
	"description": "Biscuits, Tea, Milk, Soap, Powder",
}
```
