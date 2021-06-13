# GO Protocol Buffers

-[Go Installation](https://golang.org/doc/install)

-Golang Packages :

 ```go
 go get -u github.com/golang/protobuf/protoc-gen-go
 go get -u github.com/golang/protobuf/proto
 ```

## Set up the package in the main proto source file
```go
  option go_package="file path location"
  ```
### Run the command to generate the go proto code

```go
 protoc - I <rootFoldername>/ --go_out=<finalOutputLocation>/ <path to .proto file>
 ```
