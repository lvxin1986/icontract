***Generate the protobuf class***
````
1.You should cd the path:  src/github.com/lvxin1986/icontract/tutorial
2.run the generate command:protoc -I=./ --go_out=./ ./addressbook.proto