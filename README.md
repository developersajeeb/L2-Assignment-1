## 1. What are some differences between interfaces and types in TypeScript?

In TypeScript, both interface and type are used to define the structure of objects, but there are some differences between them. Interface is mainly used to define the structure of objects, and it can be easily combined with multiple interfaces using extends. It supports declaration merging, that is, if you declare the same interface multiple times, TypeScript will merge them. On the other hand, type is much more flexible; it can also define primitive, union, intersection, tuple, etc. types, but does not support declaration merging. Interface can be used with classes by implementing them, which is not possible with a type. Interface is usually used to create clear and reusable object structures, and type is used when more complex or mixed types are needed.

## 6. How does TypeScript help in improving code quality and project maintainability?

1. TypeScript detects typos when compiling, which greatly reduces the chance of errors at runtime. This allows developers to catch errors early.
2. The type system provides advanced autocompletion, tooltips, and documentation in the IDE, which makes writing code easier and more accurate.
3. When renaming or moving functions, classes, or variables in large projects, TypeScript accurately identifies where changes need to be made, making refactoring safer and easier.
4. The type itself acts as documentation. Other developers can easily understand what inputs a function takes or what it returns.
5. Many bugs are caught early due to type and compile-time checks, which reduces the risk of problems in production.
6. TypeScript easily integrates with ESLint, Prettier, React, Angular, Node.js, etc., which helps maintain code quality.