getpass
=======

Go library that provides support for reading passwords on the command-line.

# Example
```go
import (
	"fmt"
	"github.com/dgiagio/getpass"
)

pass, _ := getpass.GetPassword("Password: ")
fmt.Printf("Entered password: %s\n", pass)
```
