# C++ features

31. [What is explicit and implicit type conversion in C++? What is the purpose of an explicit constructor?](#31-what-is-explicit-and-implicit-type-conversion-in-c-what-is-the-purpose-of-an-explicit-constructor)
32. [What is Uniform initialization? What is Aggregate initialization?](#32-what-is-uniform-initialization-what-is-aggregate-initialization)
33. [What is a Reference to temporary object? How to extend the lifetime of a temporary object?](#33-what-is-a-reference-to-temporary-object-how-to-extend-the-lifetime-of-a-temporary-object)
34. [What is a delegating constructor?](#34-what-is-a-delegating-constructor)
35. [What is initialization list?](#35-what-is-initialization-list)
36. [What is the order of class field initialization? What happens if the constructor initializes fields in a different order?](#36-what-is-the-order-of-class-field-initialization-what-happens-if-the-constructor-initializes-fields-in-a-different-order)
37. [What happens if a field is initialized with another field?](#37-what-happens-if-a-field-is-initialized-with-another-field)
38. [What is copy elision? How many times will the constructor/destructor be called for an object that is returned by value?](#38-what-is-copy-elision-how-many-times-will-the-constructordestructor-be-called-for-an-object-that-is-returned-by-value)
39. [What is move semantics?](#39-what-is-move-semantics)
40. [Under what conditions will a copy constructor be generated?](#40-under-what-conditions-will-a-copy-constructor-be-generated)
41. [What is the difference between a copy constructor and an assignment operator?](#41-what-is-the-difference-between-a-copy-constructor-and-an-assignment-operator)
42. [Under what conditions can an exception be thrown in a constructor?](#42-under-what-conditions-can-an-exception-be-thrown-in-a-constructor)
43. [What is a default constructor? What are default and delete for?](#43-what-is-a-default-constructor-what-are-default-and-delete-for)
44. [What is the difference between an interface and an abstract class?](#44-what-is-the-difference-between-an-interface-and-an-abstract-class)
45. [What are the types of polymorphism in C++?](#45-what-are-the-types-of-polymorphism-in-c)
46. [How is inheritance implemented in most compilers?](#46-how-is-inheritance-implemented-in-most-compilers)
47. [Pros and cons of multiple inheritance](#47-pros-and-cons-of-multiple-inheritance)
48. [Virtual inheritance and construction order](#48-virtual-inheritance-and-construction-order)
49. [Why use override?](#49-why-use-override)
50. [What are the rules for type deduction when using auto? In what cases can auto lead to unwanted object copying?](#50-what-are-the-rules-for-type-deduction-when-using-auto-in-what-cases-can-auto-lead-to-unwanted-object-copying)
51. [Tell about all possible ways of using the static keyword in C++. What is static initialization order fiasco?](#51-tell-about-all-possible-ways-of-using-the-static-keyword-in-c-what-is-static-initialization-order-fiasco)
52. [What does the call throw; in the catch block do?](#52-what-does-the-call-throw-in-the-catch-block-do)
53. [What is the difference between constexpr and const?](#53-what-is-the-difference-between-constexpr-and-const)
54. [What is const correctness?](#54-what-is-const-correctness)
55. [When can const_cast be used?](#55-when-can-const_cast-be-used)
56. [What is the keyword mutable and when should it be used?](#56-what-is-the-keyword-mutable-and-when-should-it-be-used)
57. [What is the keyword friend and when should it be used?](#57-what-is-the-keyword-friend-and-when-should-it-be-used)
58. [Tell us about lambda expressions in C++, accessing variables from the outer scope, capturing this in the lambda, and lifetimes of the lambda and captured variables](#58-tell-us-about-lambda-expressions-in-c-accessing-variables-from-the-outer-scope-capturing-this-in-the-lambda-and-lifetimes-of-the-lambda-and-captured-variables)
59. [What is a functor? Give an example](#59-what-is-a-functor-give-an-example)
60. [What is template specialization?](#60-what-is-template-specialization)
61. [What is dynamic_cast and run-time type identification?](#61-what-is-dynamic_cast-and-run-time-type-identification)
62. [What is an exception? How to throw and catch it?](#62-what-is-an-exception-how-to-throw-and-catch-it)
63. [What will happen if an exception is thrown from a constructor? What about a destructor?](#63-what-will-happen-if-an-exception-is-thrown-from-a-constructor-what-about-a-destructor)
64. [What will happen if an exception is not caught?](#64-what-will-happen-if-an-exception-is-not-caught)
65. [What will happen if an exception is thrown out of a noexcept function block?](#65-what-will-happen-if-an-exception-is-thrown-out-of-a-noexcept-function-block)
66. [What is private inheritance used for?](#66-what-is-private-inheritance-used-for)
67. [What is a function contract?](#67-what-is-a-function-contract)
68. [What is vptr and vtable?](#68-what-is-vptr-and-vtable)
69. [Where is vptr stored?](#69-where-is-vptr-stored)
70. [Where is vtable stored?](#70-where-is-vtable-stored)
71. [What is the difference between overload and override?](#71-what-is-the-difference-between-overload-and-override)
72. [How does the compiler differentiate between class members and regular variables in functions?](#72-how-does-the-compiler-differentiate-between-class-members-and-regular-variables-in-functions)
73. [What are exceptions used for?](#73-what-are-exceptions-used-for)
74. [What is the try-throw-catch block?](#74-what-is-the-try-throw-catch-block)
75. [Tell us about the logic of catch blocks](#75-tell-us-about-the-logic-of-catch-blocks)
76. [What is a move constructor?](#76-what-is-a-move-constructor)
77. [What is the difference between a constant method and a non-constant one?](#77-what-is-the-difference-between-a-constant-method-and-a-non-constant-one)
78. [What is Big-O notation and how to determine the complexity of any algorithm?](#78-what-is-big-o-notation-and-how-to-determine-the-complexity-of-any-algorithm)
79. [What is a virtual method table?](#79-what-is-a-virtual-method-table)
80. [What functions does the compiler automatically generate if they are defined?](#80-what-functions-does-the-compiler-automatically-generate-if-they-are-defined)
81. [What is data alignment?](#81-what-is-data-alignment)
82. [What is an exception?](#82-what-is-an-exception)
83. [What are the standard containers and what data structures are they based on?](#83-what-are-the-standard-containers-and-what-data-structures-are-they-based-on)
84. [What is Undefined behavior? Give examples](#84-what-is-undefined-behavior-give-examples)
85. [How to determine if there is a memory leak in a program?](#85-how-to-determine-if-there-is-a-memory-leak-in-a-program)
86. [What is std::make_shared used for? How is it better than creating std::shared_ptr using constructor?](#86-what-is-stdmake_shared-used-for-how-is-it-better-than-creating-stdshared_ptr-using-constructor)
87. [What will happen if you allocate one volume of memory but write more?](#87-what-will-happen-if-you-allocate-one-volume-of-memory-but-write-more)
88. [What is stack overflow?](#88-what-is-stack-overflow)

## 31. What is explicit and implicit type conversion in C++? What is the purpose of an explicit constructor?

## 32. What is Uniform initialization? What is Aggregate initialization?

## 33. What is a Reference to temporary object? How to extend the lifetime of a temporary object?

## 34. What is a delegating constructor?

## 35. What is initialization list?

## 36. What is the order of class field initialization? What happens if the constructor initializes fields in a different order?

## 37. What happens if a field is initialized with another field?

## 38. What is copy elision? How many times will the constructor/destructor be called for an object that is returned by value?

## 39. What is move semantics?

## 40. Under what conditions will a copy constructor be generated?

## 41. What is the difference between a copy constructor and an assignment operator?

## 42. Under what conditions can an exception be thrown in a constructor?

## 43. What is a default constructor? What are default and delete for?

## 44. What is the difference between an interface and an abstract class?

## 45. What are the types of polymorphism in C++?

## 46. How is inheritance implemented in most compilers?

## 47. Pros and cons of multiple inheritance

## 48. Virtual inheritance and construction order

## 49. Why use override?

## 50. What are the rules for type deduction when using auto? In what cases can auto lead to unwanted object copying?

## 51. Tell about all possible ways of using the static keyword in C++. What is static initialization order fiasco?

## 52. What does the call throw; in the catch block do?

## 53. What is the difference between constexpr and const?

## 54. What is const correctness?

## 55. When can const_cast be used?

## 56. What is the keyword mutable and when should it be used?

## 57. What is the keyword friend and when should it be used?

## 58. Tell us about lambda expressions in C++, accessing variables from the outer scope, capturing this in the lambda, and lifetimes of the lambda and captured variables

## 59. What is a functor? Give an example

## 60. What is template specialization?

## 61. What is dynamic_cast and run-time type identification?

## 62. What is an exception? How to throw and catch it?

## 63. What will happen if an exception is thrown from a constructor? What about a destructor?

## 64. What will happen if an exception is not caught?

## 65. What will happen if an exception is thrown out of a noexcept function block?

## 66. What is private inheritance used for?

## 67. What is a function contract?

## 68. What is vptr and vtable?

## 69. Where is vptr stored?

## 70. Where is vtable stored?

## 71. What is the difference between overload and override?

## 72. How does the compiler differentiate between class members and regular variables in functions?

## 73. What are exceptions used for?

## 74. What is the try-throw-catch block?

## 75. Tell us about the logic of catch blocks

## 76. What is a move constructor?

## 77. What is the difference between a constant method and a non-constant one?

## 78. What is Big-O notation and how to determine the complexity of any algorithm?

## 79. What is a virtual method table?

## 80. What functions does the compiler automatically generate if they are defined?

## 81. What is data alignment?

## 82. What is an exception?

## 83. What are the standard containers and what data structures are they based on?

## 84. What is Undefined behavior? Give examples

## 85. How to determine if there is a memory leak in a program?

## 86. What is std::make_shared used for? How is it better than creating std::shared_ptr using constructor?

## 87. What will happen if you allocate one volume of memory but write more?

## 88. What is stack overflow?
