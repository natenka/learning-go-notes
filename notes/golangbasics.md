## [Go Language Basics](https://www.golangbasics.com/)

### Intro

* Static typing
* variables of a different types are incompatible with each other
* type convertion - type casting


Types:

* int (a lot of numeric types)
* string
* slices (python list)
* maps (python dict)
* structs (python classes)

Zero value of types - variable is declared but it is not set a value:

* booleans (false)
* int (0)
* string ("")
* pointers, functions, interfaces, slices, maps (nil)

Reference types:

* slices (python list)
* maps (python dict)
* channels (synchronization primitive)

### Comments

```go
// comment
```

### Variables

```go
var x int
var x int = 10
var x = 10
```

create a var and assign the INITIAL value:

```go
x := 10
```
