# sysexits
Preferable exit codes for programs

```go
package main

import "os"
import "github.com/tit/go-sysexits"

os.Exit(sysexits.ExUsage)

```