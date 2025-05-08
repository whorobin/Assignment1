# Assignment1
 
 1. What Are the Differences Between Interfaces and Types in TypeScript?
   
Answer:
In TypeScript, both interfaces and types are used to define the shape of objects, but they have different characteristics and use cases that set them apart. Understanding the nuances between these two can significantly improve how we structure code in TypeScript.

2. WWhat is the use of the keyof keyword in TypeScript? Provide an example.

Answer:
The keyof keyword in TypeScript creates a union type of all the keys of a given object type. It helps enforce type safety by restricting values to valid keys of an object. This ensures proper access and manipulation of object properties.

interface Person {
  name: string;
  age: number;
}
type PersonKeys = keyof Person;

3. Explain the difference between any, unknown, and never types in TypeScript.

Answer:
In TypeScript, the any, unknown, and never types serve different purposes and offer varying levels of safety and flexibility. Here’s a breakdown of the differences:


4. What is the use of enums in TypeScript? Provide an example of a numeric and string enum.

Answer:
In TypeScript, enums are a way to define a set of named constants, which can be either numeric or string-based. Enums help improve code readability and maintainability by giving meaningful names to values that would otherwise be represented by numbers or strings.


5. What is type inference in TypeScript? Why is it helpful?

Answer: 
Type inference in TypeScript refers to the ability of the TypeScript compiler to automatically deduce the type of a variable, function, or expression based on its value, without needing explicit type annotations. TypeScript analyzes the assigned value and infers the most appropriate type for it.


6. How does TypeScript help in improving code quality and project maintainability?

Answer: 
TypeScript, a statically-typed superset of JavaScript, offers a range of features that significantly enhance code quality and long-term project maintainability. By providing static types, better tooling, and structured development practices, TypeScript helps catch errors early, improves code clarity, and makes collaboration more efficient.


7. Provide an example of using union and intersection types in TypeScript.

Answer: 
In TypeScript, union types and intersection types are powerful tools that allow you to create flexible and more expressive type definitions.
