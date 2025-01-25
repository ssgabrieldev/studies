# Estruturas de controle
## Estrutura for
**OBS:** Go tem apenas uma estrutura de laço, o `for`.

```go
for i := 0; i < 10; i++ {
}

```
```go
// Também pode ser escrito
i := 1
for i < 10 {
    i++
}
```
```go
// Para loops infinitos a condição é omitida
for {
}
```

## Estruturas `if` e `else`
```go
if x < 0 {
} else {
}
```
```go
// Como o `for`, a instrução `if` pode começar com uma breve declaração.
// A variável declarada só é valida no escopo até o final do `if`
if x := -1; x < 0 {
} else {
    // A variável também está disponível aqui
}
```
