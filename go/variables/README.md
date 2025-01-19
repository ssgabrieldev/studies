### Variáveis

#### Declaração
```go
// A instrução `var` declara uma lista de variáveis com o tipo sendo o último passado,
// também podendo ser passado um inicializado
var x, y int = 1, 2
```
```go
// Dentro de uma função a instrução de atribuição `:=` pode ser usada em lugar do var
func main() {
    var i, j int = 1, 2
    k := 2
    c, python, java := true, false, "no!"
}
```

#### Tipos básicos
| Tipo        | Valor Padrão     | Descrição                           |
|-------------|------------------|-------------------------------------|
| `bool`      | `false`          |                                     |
| `string`    | `""`             |                                     |
| `int`       | `0`              |                                     |
| `int8`      | `0`              |                                     |
| `int16`     | `0`              |                                     |
| `int32`     | `0`              |                                     |
| `int64`     | `0`              |                                     |
| `uint`      | `0`              |                                     |
| `uint8`     | `0`              |                                     |
| `uint16`    | `0`              |                                     |
| `uint32`    | `0`              |                                     |
| `uint64`    | `0`              |                                     |
| `uintptr`   | `0`              |                                     |
| `byte`      | `0`              |                                     |
| `rune`      | `0`              | Pseudônimo para `int32`. Representa um ponto de código Unicode. |
| `float32`   | `0`              |                                     |
| `float64`   | `0`              |                                     |
| `complex64` | `0`              |                                     |
| `complex128`| `0`              |                                     |

**OBS**: Os tipos `int`, `uint` e `uintptr` são geralmente de 32 bits em sistemas de 32 bits
e 64 bits em sistemas de 64 bits.

#### Converção
```go
// A expressão `T(v)` converte o valor `v` para o tipo `T`
var i int = 42
var f float64 = float64(i)
var u uint = uint(f)
```
