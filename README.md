# helloworld_go
[![Build Status](https://codeship.com/projects/986fc1e0-29da-0135-defa-7a0797081780/status?branch=master)](https://app.codeship.com/projects/223792)


## Building
In any case:
```
go get -v github.com/bernhardkern/helloworld_go
go build github.com/bernhardkern/helloworld_go
```
then change dir to $GOPATH/src/github.com/bernhardkern/helloworld_go
### Windows
Use git bash (and avoid firewall permissions)

```
go build && ./helloworld_go.exe -user <mysql user> <mysql password> <mysql schema>
```
### Unix
```
go run main.go -user <mysql user> <mysql password> <mysql schema>
```
