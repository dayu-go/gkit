protoc --proto_path=. --proto_path=../../../third_party --go_out=paths=source_relative:. --go-grpc_out=paths=source_relative:. --grpc-gateway_out=paths=source_relative:. ./pb/*.proto

rm -rf pb/*.go