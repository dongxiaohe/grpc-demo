GRPC demo
======================

INSTALL
-------

Need go and protc

TRY IT!
-------

1. Compile proto file
```go

protoc --go_out=plugins=grpc:. proto/helloworld/*.proto
```

2. Run the server
```go
go run go/server/main.go
```

3. Run the client
```go
go run go/client/main.go
```

