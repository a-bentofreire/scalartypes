# Description

scalartypes provides scalar types TypeScript definitions.  
  
JavaScript is a weakly typed language. TypeScript adds type definitions allowing to enforce constrains and reducing the probability runtime bugs due mixing different types of data.  
  
As TypeScript becomes widespread, compilers can take the benefit of having type information available to provide time and space optimizations.  
  
At the current state of technology, scalartypes is just **syntatic sugar**, not allowing any extra constrain enforcing by TypeScript nor any extra speed optimizations.  
But scalartypes is not only can be a valuable tool, providing more specific type information, but as well as, in the future, compilers can take advantage of it, by optimizing based on type instead of guessing.  

# Caveats

For the unaware developer, he might think that the JavaScript engine will run his code at extra speed and with less memory usage, but these types are only sugar, sweet sweet sugar.  
Since these data types aren't part of TypeScript language, TypeScript won't enforce any extra constrain as a result of using these scalar types, allowing developers to assign values that outside the type range. A unaware developer might think his code is safeguard by the TypeScript compiler.  

# Installation

`npm install @types/scalartypes`  

# Example 

## Input
```typescript
function testFunc(index: int) {  
}
```

# License

[MIT License+uuid License](https://github.com/a-bentofreire/uuid-licenses/blob/master/MIT-uuid-license.md)
