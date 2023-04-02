# Black Hat Go

This repository contains programs and code examples from the book ["Black Hat Go"](https://www.nostarch.com/blackhatgo) by Tom Steele, Chris Patten, and Dan Kottmann.

## About the Book

"Black Hat Go" is a practical guide to developing security tools and exploiting systems with Go programming language. The book covers a wide range of topics, including network scanning, port scanning, web application development, and cryptography. It also includes practical examples and code snippets that demonstrate how to use Go for security-related tasks.

## Repository Structure

This repository is organized into chapters, each containing code examples and programs related to the topics covered in the book. The structure of the repository is as follows:


# Black Hat Go Examples

```
blackhat-go/
├── chap-01
│   ├── echo_server
│   │   └── main.go
│   ├── portscanner
│   │   ├── port_scanner_channel.go
│   │   └── port_Scanner.go
│   └── Proxying_TCP_client
│       └── main.go
├── chap-02
│   ├── basics
│   │   └── main.go
│   ├── metasploit
│   │   ├── client
│   │   │   └── mian.go
│   │   ├── go.mod
│   │   ├── go.sum
│   │   └── rpc
│   │       └── msf.go
│   ├── parsing
│   │   └── main.go
│   └── shodan
│       ├── cmd
│       │   └── main.go
│       ├── go.mod
│       └── shodan
│           ├── api.go
│           ├── host.go
│           └── shodan.go
└── README.md
```






Each chapter directory contains one or more Go programs and code examples that demonstrate the concepts covered in the book. The code is organized by chapter and by individual examples.

## Requirements

To run the programs in this repository, you will need to have Go installed on your system. You can download and install the latest version of Go from the official website: https://golang.org/

## Usage

To run a program, navigate to the chapter directory that contains the program you want to run and use the `go run` command. For example, to run `port_Scanner.go` in `chap-01/portscanner`, you would use the following command:

```
#usage
cd chap-01/portscanner
go run *.go
```
