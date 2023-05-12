# URL SHORTENER API With GO

## Introduction

This is a URL shortener API built with GO. It allows users pass a long URL and it returns a shortened version that leads to the same website. However, a particular user can only pass at most 10 different URLs within 30minutes to get the shortened version. Once it exceeds 10 before 30 minutes, the program will throw an error until after 30 minutes before he can pass another URL.
So basically, this app returns a shorter versiopn of the URL that is passed to it and the URL is saved on the database and it was deployed with docker container.

##### Do the stuff below to initialize your project

1. Clone the repository
   `git clone https://github.com/Shittu24/go-jwt-auth.git`
2. Change the directory
   `cd go-jwt-auth`
3. Get all the dependencies
   `go mod tidy`
4. Run your project
   `go run main.go`

   Then go to postman and start running the routes
