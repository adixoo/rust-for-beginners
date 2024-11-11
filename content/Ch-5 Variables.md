
# Variables 

Variables are used to store data in RAM.
## Syntax

```rust
let variable_name = value;            // no type specified
let variable_name:dataType = value;   //type specified
```

## Rust Variables are immutable(Read only) by default

You can't change variable value after assigning.

```rust
let num = 123;          
num = 456; // can cause error
```

## How to make variable mutable

Prefix the variable name with `mut` keyword to make it mutable.

```rust
let mut variable_name = value;
let mut variable_name:dataType = value;
```

```rust
let mut num = 123;          
num = 456; // value updated successfully 
```

