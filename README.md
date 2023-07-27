# AVANSER PHP Coding Test

## Objective

This coding exercise serves as part of the recruitment process for Go development roles. The goal is to evaluate
your ability to make use of a new language such as Go, which may unfamiliar to some candidates.

## Task Description

You are required to complete the following task:
1. Develop a simple HTTP server using Go. The server should expose one GET endpoint /ping.
2. Develop a simple HTTP client using Go. The client should connect to the server and verify that the
output is correct, printing a result on the CLI.
3. When a GET request is made to /ping, the server should respond with a JSON payload `{ "message": "pong" }`.
4. The HTTP server should listen on port `8888`.

## Guidelines

1. You should utilize the standard net/http package provided by Go.
1. Your code must adhere to the Go coding standards, as outlined in Effective Go.
1. Proper error handling should be implemented.
2. Comment your code appropriately.

## Bonus Points

- Writing unit tests for your server.
- Packaging your application into a Docker container.
- Providing a Readme file explaining how to run your code.
- Screen recording of the client getting a response from the server process.

## Tips

- Instruction for downloading and installing Go are available at [https://go.dev/doc/install](https://go.dev/doc/install)
- Documentation for Go is available at [https://go.dev/learn/](https://go.dev/learn/)
- Run your server locally during development and make sure all requests return the expected results.
- It's recommended to use `go-critic`, `go fmt` and `go vet` to keep your code clean and error-free.
- You can use tools like Postman or `curl` to test your endpoints.
- Remember to include instructions on how to run your code and any dependencies that must be installed beforehand.