Go UUID
=======

Simple, dumb UUID generator.

For now, only generates a v4, random guid. Perhaps more later, but no plans at this time as this works for my current use.

Sample Use:
```go
package main

import (
  "fmt"
  "github.com/victorquinn/go-uuid"
)

func main() {
  // get and print a uuid
  fmt.Println(uuid.Generate())
}

```

Originally pulled from [this post](https://groups.google.com/forum/#!msg/golang-nuts/d0nF_k4dSx4/rPGgfXv6QCoJ)
