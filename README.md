# golangWithgRPC


## 참조 
- https://grpc.io/docs/languages/go/quickstart/
- https://lejewk.github.io/grpc-go-example/
    - follow 하다가 protoc 실행하는 부분에 대해서 나와있지 않아서 제외.
- 


## 환경 
- mac os 10.14.6
- golang version : 1.12.1


grpc

mac 
1. 최신의 golang 
2. protobuf 
 brew install protobuf


cd grpc-go/examples/helloworld
 go run greeter_server/main.go 
 # 서버 띄움 

 other terminal 
 cd grpc-go/examples/helloworld
 go run greeter_client/main.go
 # client 에서 