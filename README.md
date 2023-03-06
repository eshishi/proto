# proto
## install protoc
[windows](github.com/google/protobuf/releases)
or 
`brew install protobuf`
```
go install -v github.com/stormcat24/protodep@v0.1.7
```
`protodep.toml`
```toml
proto_outdir = "./proto"

[[dependencies]]
target = "https://github.com/eshishi/proto"
```
```
protodep up
```
