# Installing woojin
First, you need Rust to use woojin. If you don't already have Rust installed on your computer, [click here](https://doc.rust-lang.org/cargo/getting-started/installation.html) to learn how to install Rust.

If Rust is installed, you can open the terminal and run the command below to install woojin.
```text
$ cargo install woojin --all-features
```
Woojin is now installed! Congratulations! Then, let's make and run a simple Woojinlang example. Let's go to any directory, create a file called 'example.wj', and enter the same code below. The code below is a simple program that asks the user for a name and prints it out.
```woojin
println "My First Woojinlang Program!";
let name = input "Hello, What is your Name? ";
println "Hello, "+$name+". Nice to meet you!";
yee 0;
```
Now let's run the command below, and run the woojin code above.
```text
$ woojin example.wj
```
