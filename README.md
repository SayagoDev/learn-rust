# RUST

## Fundamentals

### Data Types
- Boolean
- Integer
- Double & float
- Character
- String

### Variables
* Assign data to a temporary memory location
    * Allows Programmer to easily work with memory
* Immutable by default, but can be mutable

```rust
let j = 'j';
let two = 2;
let my_half = 0.5;
let mut my_name = "Angel";
let quit_program = false;
let your_half = my_half;
```

### Functions
* A way to encapsulate program functionality
* Optionally accept data
* Optionally return data
* Utilized for code organization
    * Also makes code easier to read

```rust
fn add(a: i32, b: i32) -> i32 {
    a + b
}

let x = add(1, 1);
let y = add(3, 0);
let z = add(x, 1);
```

### Println Macro
* "Prints" (displays) information to the terminal
* Macros use an exclamation point to call
* Generate additional Rust code
* Useful for debugging

```rust
let life = 42;
println!("hello");
println!("{:?}", life);
println!("{:?} {:?}", life, life);
```
