# Variables and Mutability
woojin, being a programming language based on Rust, has been heavily influenced by Rust syntax. Similar to Rust, variables in woojin are immutable by default. Variables are inherently immutable. If you want to declare a mutable variable, you can include the mut keyword in the variable declaration. The following woojin code demonstrates this concept.

```woojin
let a = 1; // Declare int type variable a (immutable variable)
let mut b = 1; // Declare int type variable b (mutable variable)
```
> **Note:** Due to the developer's mistake, in the current v0.1.x version, it is impossible to change the value of the variable after declaring it. This problem will be solved soon. We're so sorry.