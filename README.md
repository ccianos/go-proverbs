```
 ______________________________________
/ The bigger the interface, the weaker \
\ the abstraction.                     /
 --------------------------------------
        \    ,-^-.
         \   !oYo!
          \ /./=\.\______
               ##        )\/\
                ||-----w||
                ||      ||

               Cowth Vader
```

> Go Proverbs as a package and command.

[![Build Status](https://travis-ci.org/wayneashleyberry/go-proverbs.svg?branch=master)](https://travis-ci.org/wayneashleyberry/go-proverbs)
[![Go Report Card](https://goreportcard.com/badge/github.com/wayneashleyberry/go-proverbs)](https://goreportcard.com/report/github.com/wayneashleyberry/go-proverbs)
[![GoDoc](https://godoc.org/github.com/wayneashleyberry/go-proverbs?status.svg)](https://godoc.org/github.com/wayneashleyberry/go-proverbs)

### What are Go proverbs?

Check out [Rob Pike's](https://twitter.com/rob_pike) inspiring [talk at Gopherfest SV 2015](https://www.youtube.com/watch?v=PAAkCSZUG1c).

### Usage

#### Command

```sh
go get github.com/wayneashleyberry/go-proverbs/...
```

```sh
$ goproverb
Design the architecture, name the components, document the details.
```

#### Package

```sh
go get github.com/wayneashleyberry/go-proverbs/
```

```go
package main

import (
	"fmt"

	p "github.com/wayneashleyberry/go-proverbs"
)

func main() {
	fmt.Println(p.Random()) // Prints a random Go proverb.
}
```

### License

MIT © [Wayne Ashley Berry](https://wayne.cloud)
