# AVANSER PHP Coding Test

## Objective

This coding exercise serves as part of the recruitment process for Go development roles. The goal is to evaluate
your ability to make use of a new language such as Go, which may unfamiliar to candidates.

## Task Description

You are required to complete the following task:
1. Develop a simple HTTP server using Go. The server should expose one GET endpoint /ping.
1. When a GET request is made to /ping, the server should respond with a JSON payload `{ "message": "pong" }`.
1. The HTTP server should listen on port `8888`.

## Guidelines

1. You should utilize the standard net/http package provided by Go.
1. Your code must adhere to the Go coding standards, as outlined in Effective Go.
1. Proper error handling should be implemented.

## Bonus Points

- Writing unit tests for your server.
- Packaging your application into a Docker container.
- Providing a Readme file explaining how to run your code.

## Tips

- Instruction for downloading and installing Go are available at [https://go.dev/doc/install](https://go.dev/doc/install)
- Documentation for Go is available at [https://go.dev/learn/](https://go.dev/learn/)
- Run your server locally during development and make sure all requests return the expected results.
- It's recommended to use `go fmt` and `go vet` to keep your code clean and error-free.
- You can use tools like Postman or `curl` to test your endpoints.
- Remember to include instructions on how to run your code and any dependencies that must be installed beforehand.