# foo 

A gpk.io sample package.

```golang
package main

import (
  "fmt"
  
  "gpk.io/foo"
  foov2 "gpk.io/foo.v2"
  foorework "gpk.io/foo.rework"
)

func main() {
  fmt.Printf("foo.Version(): %s", foo.Version())
  fmt.Printf("foov2.Version(): %s", foov2.Version())
  fmt.Printf("foorework.Version(): %s", foorework.Version())
}
```
