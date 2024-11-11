# Constants

Constants represent values that cannot be changed or you can say they are always immutable.

```rust
const VARIABLE_NAME:dataType = value;
```

You can't use `mut` keyword with `const`

```rust
const mut VARIABLE_NAME:dataType = value; // this will cause error
```


## Variables vs Costants

|     | Variables                               | Constants                              |
| --- | --------------------------------------- | -------------------------------------- |
| 1   | Declared using the `let` keyword        | Declared using the `const` keyword     |
| 2   | Can optionally have a data type         | Declaration must specify the data type |
| 3   | Immutable by default but can be mutable | Are always immutable                   |


