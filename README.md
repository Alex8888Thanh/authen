# authen
Authentication and Authorization in Go using JWT(JSON Web Tokens)

Initializing with go.mod

Downloading dependencies
Next, we will download the required dependencies. We will use

mux for routing and handling HTTP requests
GORM as ORM tool
crypto for password hashing
Postgres for the database

$ go get github.com/gorilla/mux
$ go get github.com/jinzhu/gorm
$ go get golang.org/x/crypto/bcrypt

Downloading jwt-package
Download the jwt package using this command-

go get github.com/golang-jwt/jwt

....

go run authenticate-jwt.go
