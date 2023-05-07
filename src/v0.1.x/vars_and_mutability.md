# Variables and Mutability
woojin, being a programming language based on Rust, has been heavily influenced by Rust syntax. Similar to Rust, variables in woojin are immutable by default. Variables are inherently immutable. If you want to declare a mutable variable, you can include the mut keyword in the variable declaration. The following woojin code demonstrates this concept.

```woojin
let a = 1; // Declare int type variable a (immutable variable)
let mut b = 1; // Declare int type variable b (mutable variable)
```
> **Note:** Due to the developer's mistake, in the current v0.1.x version, it is impossible to change the value of the variable after declaring it. This problem will be solved soon. We're so sorry.

To use a declared variable in woojin, you can simply prefix the variable name with a `$` symbol. So, to use the variable a that was declared earlier, you would write `$a`, and to use the variable b, you would write `$b`. This approach was chosen because it is easy to implement and it allows you to declare variables with names that may conflict with system standard functions (e.g., `input`, `roar`).
Let's take a look at an example that uses the variables a and b declared earlier:
```woojin
println $a;
println $a + $b;
```
In the above code, the first println statement prints the value of `$a`, and the second println statement performs an addition between `$a` and `$b` and prints the result. By using the $ symbol, you can easily reference the values of variables in your program.