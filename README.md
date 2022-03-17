# beam-go

## Nandini Kandi

### Instructions to install and run successfull beam-go project

1. Install [GO](https://go.dev/)
2. Open powershell and Check go version to make sure that it is installed   
 ```go version```
3. Create beam-go directory in 44517 folder
``` mkdir beam-go```
4. Go to the directory
```cd beam-go```
5. Install Apache Beam Go SDK using
```$ go get -u github.com/apache/beam/sdks/v2/go/pkg/beam```
6. Create wordcount.go from [here](https://github.com/apache/beam/tree/master/sdks/go/examples/wordcount)
7. create sample.txt with some content
8. Build wordcount.go 
```go build wordcount.go```
9. Run wordcount.go by passing arguments sample.txt as input and output.txt as output
```.\wordcount --input sample.txt --output output.txt```
 
