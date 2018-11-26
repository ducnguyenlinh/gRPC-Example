# Generate
protoc -I ../grpcExample --go_out=plugins=grpc:../grpcExample ../grpcExample/grpcExample/grpcExample.proto
# Or
protoc -I grpcExample/ grpcExample/grpcExample.proto --go_out=plugins=grpc:grpcExample
