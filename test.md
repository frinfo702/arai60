```rust
use std::io;

fn main() {
    println!("Please enter a greeting");
    let mut name = String::new();
    io::stdin().read_line(&mut name).expect("Failed to read");

    println!("{}", name.trim_matches('!'));
    println!("{}", name.trim_matches('!'));    
}

```
