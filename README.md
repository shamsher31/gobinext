# gobinext

[![Godoc](http://img.shields.io/badge/godoc-reference-blue.svg?style=flat)](https://godoc.org/github.com/shamsher31/gobinext)
[![Build Status](https://travis-ci.org/shamsher31/gobinext.svg)](https://travis-ci.org/shamsher31/gobinext)

List of binary file extensions for Go

### How to install
```go
go get github.com/shamsher31/gobinext
```

### How to use
```go
package main

import (
	"fmt"
	"github.com/shamsher31/gobinext"
)

func main() {
	fmt.Println(binext.Get())
}
```

### Why
This package is inspired by [binary-extensions](https://www.npmjs.com/package/binary-extensions) npm module.

### License
MIT © [Shamsher Ansari](https://github.com/shamsher31)
