# learning-go

This is a learning project

## Setting the proyect

First of all you need to initialice the proyect by executing
```shell
go mod init

# or to add the module name
go mod init example/hello
```
This will create a file go.mod in the directory, this file is necesary only when you execute "go test" or "go build" if you do a simple "go run" it will be not necesary

## Compile and execute

You can execute a go file directly by launching the command
```shell
go run my_program.go
```

You can compile and generate and executable file by
```shell
go build my_program.go

# and after that
./my_program
```

## Project files

hello # first directory with a simple "hello world" example

## Resources

1. [Getting started](https://go.dev/doc/tutorial/getting-started)
2. [A Go tour](https://go-tour-lat.appspot.com/welcome/1)
3. [Learn go with test](https://quii.gitbook.io/learn-go-with-tests)
4. [Go documentation](https://go.dev/doc/)
5. [Leanr in x minutes](https://learnxinyminutes.com/docs/go/)
