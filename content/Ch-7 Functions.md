# Functions

Functions are reusable block of codes that can be called when needed.

```rust
fn main() { 
	println!("Hello, world!"); 
	i_am_another_function(); // rust use snake case for function naming
} 

fn i_am_another_function() { 
	println!("Hello from Another function."); 
}
```

## Passing parameters and return type

```rust
fn main() {
    let num1 = 12;
    let num2 = 56;
    
    let result = add(num1, num2);
    println!("The result is: {result}");

}
fn add(num1: i32, num2: i32) -> i32 {
    num1 + num2
}
```

