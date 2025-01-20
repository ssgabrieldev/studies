# Package

## Definição de um package
```go
// Cada programa Go é composto de pacotes onde o pacote de entrada é o `main`.
package main

// Por convenção, o nome do pacote é o mesmo que o último do caminho da importação.
import (
    "fmt",
    // Ex: o pacote "math/rand" compreende arquivos que começam com `package rand`.
    "math/rand"
)
```

## Importação
```go
package main

// Por boa prática os imports devem ser agrupados em parenteses, mas podem ser
// importados separadamente.

// Ex:
// import "fmt"
// import "math"

import (
    "fmt",
    "math"
)
```

## Exportação
```go
package main

import (
    "fmt",
    "math"
)

func main() {
    // Em Go, um nome é exportado se ele começa com uma letra maiúscula.
    // `Pi` é exportado do pacote `math`
    fmt.Prinln(math.Pi)
}
```
