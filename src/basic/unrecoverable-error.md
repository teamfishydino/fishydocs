# Crate a unrecoverable Error
There are times when it is necessary to generate unrecoverable errors in a program. For example, when a user inputs a value outside the allowed range or fails to provide essential information required for the program to function properly. In such cases, it is often necessary to generate an unrecoverable error and terminate the program.

In woojin, a simple mechanism exists to generate unrecoverable errors using the `roar` keyword. For instance:
```woojin
roar "It seems that all the necessary information to run the program has not been provided.";
```
The above code will display the error message "It seems that all the necessary information to run the program has not been provided." and terminate the program. This can be useful when users fail to provide essential information required for the program to execute. However, it is important to note that the error message should be concise, clear, and effectively communicate the issue at hand.