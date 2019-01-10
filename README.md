# sysexits
Preferable exit codes for programs

https://developer.apple.com/library/archive/documentation/System/Conceptual/ManPages_iPhoneOS/man3/sysexits.3.html

```go
package main

import "os"
import "github.com/tit/go-sysexits"

func main(){
  os.Exit(sysexits.ExUsage)
}
```