# String

A sequence of characters is known as string. String is data type.

There are two methods of creating string.
- String Literal
- String Object

## String Literal (Method - 1)

String literals are used when the value of a string is known at compile time. String literals are a set of characters, which are hardcoded into a variable.

```rust
fn main() {
   let company:&str="Google";
   let location:&str = "Hyderabad";
   println!("company is : {} location :{}",company,location);
}
```

String literals are fast and efficient this is because of there immutability.
## String Object (Method - 2)

In some cases we need to change string values, where we don't know the exact size.