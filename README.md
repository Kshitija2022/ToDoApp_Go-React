# Go To Do App

This is a to-do list application.

Server: Golang  
Client: React
Database: MongoDB

# Highlights

1. DB connection string, name and collection name is in `.env` file as environment variable. Using `github.com/joho/godotenv` to read the environment variables.

# Application Requirement

# golang server requirement

1. golang https://golang.org/dl/
2. gorilla/mux package for router `go get -u github.com/gorilla/mux`
3. mongo-driver package to connect with mongoDB `go get go.mongodb.org/mongo-driver`
4. github.com/joho/godotenv to access the environment variable.

# react client

From the Application directory

`create-react-app client`

## :computer: Start the application

1. Make sure your mongoDB is started
2. Create a `.env` file inside the `go-server` and update the DB connection string.
3. From go-server directory, open a terminal and run
   `go run main.go`
4. From client directory,  
   a. install all the dependencies using `npm install`  
   b. start client `npm start`

## Walk through the application

Open application at http://localhost:3000
