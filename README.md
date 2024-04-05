# Description

gRpc SSO serice using golang and protobuf  
//
# Project structure
```
├── go.work
├── go.work.sum
├── protos  // protobuf generated file
│   ├── gen
│   │   └── go
│   │       └── proto
│   │           └── sso
│   │               ├── sso_grpc.pb.go
│   │               └── sso.pb.go
│   ├── go.mod
│   ├── go.sum
│   └── proto // .proto files
│       └── sso
│           └── sso.proto
├── README.md
└── sso
    ├── cmd // run applicatio
    │   └── sso
    │       └── main.go
    ├── config // config
    │   └── local.yaml
    ├── go.mod
    └── internal 
        └── config.go // load configuration
```
