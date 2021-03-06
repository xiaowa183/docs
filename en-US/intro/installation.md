---
name: Installation
---

# Installation

Since we haven't had binary distribution yet, you have to know how to install and setup [Go](https://golang.org/) environment to get started with.

## From Source Code

Install from source code requires you have setup [Go](https://golang.org/) environment and set `$GOPATH` variable correctly.

You can check them with following commands:

```sh
$ go version
go version go1.5.1 darwin/amd64
$ echo $GOPATH
~unknwon/go
```

The minimum requirement version of Go is **1.3**.

You can then install Peach by executing following command:

```sh
go get github.com/peachdocs/peach
```

Add `-u` flag to update Peach:

```sh
go get -u github.com/peachdocs/peach
```

You can then use following command to check which version of Peach is installed on your system (Suppose `$GOPATH/bin` has been added to your `$PATH`):

```sh
$ peach -v
Peach version 0.8.0.1025
```
