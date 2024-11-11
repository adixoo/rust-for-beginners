
## Prerequirties 

- String
- Variables

---


**Ownership** is a set of rules that govern how a Rust program manages memory.

Every program manages RAM usage, and different languages have various ways of handling memory management.

In programming languages like C, we explicitly have to allocate and free RAM on our own. In the case of JavaScript, they use a garbage collector that always checks whether a variable is needed or not.

Ownership is a new approach.


## Variable Scope

A scope is the range within a program for which an item is valid.

```rust
{
	// st is not valid here
	let st = "Hello"; // st is valid here
	// st is valid here
}
// st is not valid here
```


## Memory Allocation

Memory allocation in rust is depends on variable scoping.

```rust
{
	// st is not valid here
	let st = "Hello"; // st is valid here
	// st is valid here
}
// st is not valid here
```

When a variable goes out of scope rust automatically calls a function `drop` to free memory.

## Ownership Rules

-  Each value in Rust has an _owner_.
-  There can only be one owner at a time.
-  When the owner goes out of scope, the value will be dropped.




