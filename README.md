# install go

https://go.dev/doc/manage-install
https://go.dev/doc/install

:~/hello$ sudo go version
go version go1.22.5 linux/amd64

# new file
go mod init example/hello

create a file hello.go

```
package main

import "fmt"

func main() {
    fmt.Println("Hello, World!")
}
```
# run : sudo go run .
https://go.dev/doc/tutorial/getting-started

