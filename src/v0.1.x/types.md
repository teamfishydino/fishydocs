# Types
The supported types in woojin.

## Scalar value
### bool
In a typical programming language, bool types are used to express `true` and `false`. But it's a little different in the Woojin language. In woojin, we label `true` as `uglyguri` and `false` as `beautifulguri` **because the younger sister of one of the developers of the woojin language is nicknamed guri.**
### int
It represents signed integers. In the `int` data type, values ranging from \(2^{31}\) (-2,147,483,648) to \(2^{31}-1\) (2,147,483,647) can be represented. In other words, internally, this type is represented as Rust's `i32` type.
### long
It is a data type that represents signed integers, similar to the `int` type. However, the `long` type can represent values ranging from \(2^{63}-\) (-9,223,372,036,854,775,808) to \(2^{63}-1\) (9,223,372,036,854,775,807). Internally, this type is represented as `i64`.
### float
It is a data type that can represent single-precision (32-bit) floating-point numbers. In versions prior to v0.1.x, there is no type available to represent double-precision (64-bit) floating-point numbers. Therefore, in those versions or any earlier versions, this is the only type available to represent floating-point numbers.

## Compound Types
"Compound type" refers to a type that combines multiple values into a single entity, allowing for the representation of data structures where multiple values coexist together. It enables the expression of data structures in which multiple values exist simultaneously.
### array
Despite the efforts to implement the array type in woojin, it eventually proved to be unsuccessful. As a result, in the v0.1.x version, the array type is not available. However, the good news is that the implementation of the array type is planned for the near future, and it will be available soon.