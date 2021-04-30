# protos
* Repository for all proto definitions.

Installation:

Via HomeBrew
```
brew install protoc-gen-go grpc
```

Buf to lint the proto:
```
brew install bufbuild/buf/buf
brew install buf
```

Generating:

```
protoc -I=$SRC_DIR --go_out=plugins=$DST_DIR $SRC_DIR/currency-exchange.proto
```

linting:

```
brew install prototool

prototool lint 
```

