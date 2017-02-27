# Gorilla with Docker

This is a small Gorilla Mux application that outputs "Gorilla!". 

## Basics

- Clone this repository
- Install dependencies
- - w/ `Glide` --> `glide install`
- - **or** `go get github.com/gorilla/mux`
- Build docker image
- - Inside the repository build command: `docker build -t hello-gorilla .`
- Run docker image
- - `docker run --publish 6060:8080 --name hello-gorilla --rm hello-gorilla`
- Check the application @ [localhost:6060](http://127.0.0.1:6060)
- Stop docker image
- - `docker stop hello-gorilla`
