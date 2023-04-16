# Golang Cheatsheet

## Loops

There is only one loop in Go and that is the keyword `for`.

### Infite Loop

```go
for {
    // Infinite loop
}
```

You can exit the infite loop with they keyword `break`. 

### Conditional Loop

```go
x := 0
for x < 10 {
    fmt.Println("x =", x)
    x++
}
```

### Traditional for loop

```go
for x := 0; x < 10; x++ {
    fmt.Println("x =", x)
}
```
