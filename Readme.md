# Go-gRPC
This is simple demonstration of how grpc is to be used with golang.

1. SimpleGRPC is demo of how unary type of grpc communication or api works
For simple/unary grpc sample.pb.go file is generated by executing following command:
   ~~~ 
   protoc -I ProtoDir/  ./ProtoDir/sample.proto --go_out=plugins=grpc:ProtoDir/ 
   ~~~
   
In this simple addition and subtraction utility is demonstrated through unary grpc   

2. Server Side Streaming type of grpc is explained with the help of small example of finding Divisors of number.
For server side streaming grpc serverStreamingProto.pb.go file is generated by executing following command:
  ~~~
  protoc -I ServerSideStreaming/ServerSideStreamingProto/ ./ServerSideStreaming/ServerSideStreamingProto/serverStreamingProto.proto --go_out=plugins=grpc:ServerSideStreaming/ServerSideStreamingProto/
  ~~~


3. Client Side Streaming type of grpc is explained with the help of small example of finding max number from stream of number.
For client side streaming grpc clientstraming.pb.go file is generated by executing following command:
 ~~~
  protoc -I ClientSideStramingGRPC/ClientSideStramingProto/ ./ClientSideStramingGRPC/ClientSideStramingProto/clientstraming.proto --go_out=plugins=grpc:ClientSideStramingGRPC/ClientSideStramingProto/
 ~~~ 

4. Bidirectional Streaming type of grpc is explained with the help of small example of finding max number from stream of number.
For bidirectional streaming grpc bidirctionalProto.pb.go file is generated by executing following command:
 ~~~
  protoc -I BiDirectionGRPC/BiDirProto/  ./BiDirectionGRPC/BiDirProto/bidirctionalProto.proto --go_out=plugins=grpc:BiDirectionGRPC/BiDirProto/
 ~~~
Small Presentation on grpc: https://drive.google.com/open?id=1_-zI9DtOOa-LYHC79Bdi8YYlIDMt46KISFh35wvaZxI
