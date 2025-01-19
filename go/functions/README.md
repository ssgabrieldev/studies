###  Funções

#### Parametros
```go
// Quando dois ou mais parâmetros nomeados consecutivos de uma função compartilham
// o mesmo tipo, você pode omitir o tipo de todos menos o útimo pois **o tipo vem à direita**
func add(x, y int) int {
    return x + y
}
```

#### Retorno
```go
// Uma função pode retornar qualquer número de resultados
func swap(x, y string) (string, string) {
    return y, x
}

func main() {
    a, b := swap("hello", "world")
    fmt.Println(a, b)
}
```
```go
// Valores de retorno podem ser nomeados e agirem apenas como variáveis
func swap(x, y string) (x, y int) {
    x = sum * 4/9
    y = sum - x

    // O `return` sem argumentos retorna os valores atuais dos resultados
    // devem ser usadas apenas em funções curtas, pois prejudica a legibilidade
    return
}

func main() {
    a, b := swap("hello", "world")
    fmt.Println(a, b)
}
```

