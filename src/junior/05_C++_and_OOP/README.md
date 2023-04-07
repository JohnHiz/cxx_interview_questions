# C++ & Object-oriented programming

54. [What is a class?](#54-what-is-a-class)
55. [What are the general data types in C++?](#55-what-are-the-general-data-types-in-c)
56. [What is encapsulation? How is it implemented in C++?](#56-what-is-encapsulation-how-is-it-implemented-in-c)
57. [What are the built-in types in C++?](#57-what-are-the-built-in-types-in-c)
58. [What is an enum?](#58-what-is-an-enum)
59. [How does a class relate to an object?](#59-how-does-a-class-relate-to-an-object)
60. [What is the difference between a structure and a class?](#60-what-is-the-difference-between-a-structure-and-a-class)
61. [What is the difference between private/protected/public and where are they used?](#61-what-is-the-difference-between-privateprotectedpublic-and-where-are-they-used)
62. [What methods of a class are standard for a class?](#62-what-methods-of-a-class-are-standard-for-a-class)
63. [What is an abstract class and what is it used for?](#63-what-is-an-abstract-class-and-what-is-it-used-for)
64. [How much memory does an empty object class A{}; take up?](#64-how-much-memory-does-an-empty-object-class-a-take-up)
65. [What happens to a function if the static keyword is added? In the context of a class member? In the context of a class method?](#65-what-happens-to-a-function-if-the-static-keyword-is-added-in-the-context-of-a-class-member-in-the-context-of-a-class-method)
66. [What are the characteristics of static class fields?](#66-what-are-the-characteristics-of-static-class-fields)
67. [What is special about constant class member methods?](#67-what-is-special-about-constant-class-member-methods)
68. [How to change a class field in a constant class method?](#68-how-to-change-a-class-field-in-a-constant-class-method)
69. [What methods can be called from constant objects?](#69-what-methods-can-be-called-from-constant-objects)
70. [What is the heap and stack? Differences, working principle.](#70-what-is-the-heap-and-stack-differences-working-principle)
71. [What is the difference between a pointer and a reference?](#71-what-is-the-difference-between-a-pointer-and-a-reference)
72. [What is a pointer to a function used for? How to declare it?](#72-what-is-a-pointer-to-a-function-used-for-how-to-declare-it)
73. [What happens if you forget to call delete? When will that memory be freed?](#73-what-happens-if-you-forget-to-call-delete-when-will-that-memory-be-freed)
74. [What is a smart pointer? What smart pointers are there in the standard library?](#74-what-is-a-smart-pointer-what-smart-pointers-are-there-in-the-standard-library)
75. [How does std::unique_ptr work?](#75-how-does-stdunique_ptr-work)
76. [How does std::shared_ptr work?](#76-how-does-stdshared_ptr-work)
77. [What is the constantness of a variable, reference, and pointer? What is a constant pointer and a pointer to a constant? What is the size of a pointer in memory?](#77-what-is-the-constantness-of-a-variable-reference-and-pointer-what-is-a-constant-pointer-and-a-pointer-to-a-constant-what-is-the-size-of-a-pointer-in-memory)
78. [Explain the passing of arguments by value, reference and pointer.](#78-explain-the-passing-of-arguments-by-value-reference-and-pointer)
79. [Explain the order of function argument evaluation.](#79-explain-the-order-of-function-argument-evaluation)
80. [What will happen if you return a reference to a temporary object?](#80-what-will-happen-if-you-return-a-reference-to-a-temporary-object)
81. [What is function overloading? What are the types of overloading?](#81-what-is-function-overloading-what-are-the-types-of-overloading)
82. [What are explicit and implicit type conversions in C++? Explain the functions of explicit type conversion in C++.](#82-what-are-explicit-and-implicit-type-conversions-in-c-explain-the-functions-of-explicit-type-conversion-in-c)
83. [What is variable initialization in an if statement?](#83-what-is-variable-initialization-in-an-if-statement)
84. [What are lazy evaluations in C++?](#84-what-are-lazy-evaluations-in-c)
85. [Explain the for and range-for loops.](#85-explain-the-for-and-range-for-loops)
86. [What does the auto keyword do? Auto-deduction of return type and function arguments?](#86-what-does-the-auto-keyword-do-auto-deduction-of-return-type-and-function-arguments)
87. [What is the difference between delete and delete[]? What will happen if you call delete on an object created with new[]?](#87-what-is-the-difference-between-delete-and-delete-what-will-happen-if-you-call-delete-on-an-object-created-with-new)
88. [Error handling in C++. What language constructs are used in exception handling?](#88-error-handling-in-c-what-language-constructs-are-used-in-exception-handling)
89. [Can an exception be thrown from a constructor? What fields will be constructed, what fields will be destroyed?](#89-can-an-exception-be-thrown-from-a-constructor-what-fields-will-be-constructed-what-fields-will-be-destroyed)
90. [What is a memory leak?](#90-what-is-a-memory-leak)
91. [Can an exception be thrown from a destructor?](#91-can-an-exception-be-thrown-from-a-destructor)
92. [How can division by 0 be caught in C++?](#92-how-can-division-by-0-be-caught-in-c)
93. [How do constant methods work?](#93-how-do-constant-methods-work)
94. [What is a lambda function in C++? How to access variables in an outer scope?](#94-what-is-a-lambda-function-in-c-how-to-access-variables-in-an-outer-scope)
95. [What is the use of a namespace and anonymous namespace?](#95-what-is-the-use-of-a-namespace-and-anonymous-namespace)
96. [How to call an object with a nested namespace?](#96-how-to-call-an-object-with-a-nested-namespace)
97. [How do inline functions work? Can such a function be recursive?](#97-how-do-inline-functions-work-can-such-a-function-be-recursive)
98. [What is polymorphism?](#98-what-is-polymorphism)
99. [What is inheritance used for?](#99-what-is-inheritance-used-for)
100. [What types of inheritance are there?](#100-what-types-of-inheritance-are-there)
101. [What is virtual inheritance used for?](#101-what-is-virtual-inheritance-used-for)
102. [How can the diamond problem be solved without using virtual inheritance?](#102-how-can-the-diamond-problem-be-solved-without-using-virtual-inheritance)
103. [What will happen if a derived class is passed by value to a function that takes a base class?](#103-what-will-happen-if-a-derived-class-is-passed-by-value-to-a-function-that-takes-a-base-class)
104. [What will happen if a base class with no virtual constructor is inherited from?](#104-what-will-happen-if-a-base-class-with-no-virtual-constructor-is-inherited-from)
105. [What will happen if a virtual function is called from a constructor? Can a constructor be virtual?](#105-what-will-happen-if-a-virtual-function-is-called-from-a-constructor-can-a-constructor-be-virtual)
106. [Can a pure virtual function have an implementation? What will happen if a pure virtual function is called from a constructor?](#106-can-a-pure-virtual-function-have-an-implementation-what-will-happen-if-a-pure-virtual-function-is-called-from-a-constructor)
107. [What methods are generated for a class by default? In what cases will these methods not be generated? How can you make a compiler add/remove these methods?](#107-what-methods-are-generated-for-a-class-by-default-in-what-cases-will-these-methods-not-be-generated-how-can-you-make-a-compiler-addremove-these-methods)
108. [How can you prevent a class from being inherited from?](#108-how-can-you-prevent-a-class-from-being-inherited-from)
109. [What is the order of constructing and destructing classes in the hierarchy? What is the order of initialization of the class fields?](#109-what-is-the-order-of-constructing-and-destructing-classes-in-the-hierarchy-what-is-the-order-of-initialization-of-the-class-fields)
110. [What are the ways to initialize class fields?](#110-what-are-the-ways-to-initialize-class-fields)
111. [Can a destructor be virtual?](#111-can-a-destructor-be-virtual)
112. [What does the keyword virtual do?](#112-what-does-the-keyword-virtual-do)
113. [What is a virtual destructor used for?](#113-what-is-a-virtual-destructor-used-for)
114. [What is deep copying?](#114-what-is-deep-copying)
115. [What are virtual functions and what are they used for?](#115-what-are-virtual-functions-and-what-are-they-used-for)
116. [How can an object be protected from copying?](#116-how-can-an-object-be-protected-from-copying)
117. [What is move semantics?](#117-what-is-move-semantics)

## 54. What is a class?

## 55. What are the general data types in C++?

## 56. What is encapsulation? How is it implemented in C++?

## 57. What are the built-in types in C++?

## 58. What is an enum?

## 59. How does a class relate to an object?

## 60. What is the difference between a structure and a class?

## 61. What is the difference between private/protected/public and where are they used?

## 62. What methods of a class are standard for a class?

## 63. What is an abstract class and what is it used for?

## 64. How much memory does an empty object class A{}; take up?

## 65. What happens to a function if the static keyword is added? In the context of a class member? In the context of a class method?

## 66. What are the characteristics of static class fields?

## 67. What is special about constant class member methods?

## 68. How to change a class field in a constant class method?

## 69. What methods can be called from constant objects?

## 70. What is the heap and stack? Differences, working principle

## 71. What is the difference between a pointer and a reference?

## 72. What is a pointer to a function used for? How to declare it?

## 73. What happens if you forget to call delete? When will that memory be freed?

## 74. What is a smart pointer? What smart pointers are there in the standard library?

## 75. How does std::unique_ptr work?

## 76. How does std::shared_ptr work?

## 77. What is the constantness of a variable, reference, and pointer? What is a constant pointer and a pointer to a constant? What is the size of a pointer in memory?

## 78. Explain the passing of arguments by value, reference and pointer

## 79. Explain the order of function argument evaluation

## 80. What will happen if you return a reference to a temporary object?

## 81. What is function overloading? What are the types of overloading?

## 82. What are explicit and implicit type conversions in C++? Explain the functions of explicit type conversion in C++

## 83. What is variable initialization in an if statement?

## 84. What are lazy evaluations in C++?

## 85. Explain the for and range-for loops

## 86. What does the auto keyword do? Auto-deduction of return type and function arguments?

## 87. What is the difference between delete and delete[]? What will happen if you call delete on an object created with new[]?

## 88. Error handling in C++. What language constructs are used in exception handling?

## 89. Can an exception be thrown from a constructor? What fields will be constructed, what fields will be destroyed?

## 90. What is a memory leak?

## 91. Can an exception be thrown from a destructor?

## 92. How can division by 0 be caught in C++?

## 93. How do constant methods work?

## 94. What is a lambda function in C++? How to access variables in an outer scope?

## 95. What is the use of a namespace and anonymous namespace?

## 96. How to call an object with a nested namespace?

## 97. How do inline functions work? Can such a function be recursive?

## 98. What is polymorphism?

## 99. What is inheritance used for?

## 100. What types of inheritance are there?

## 101. What is virtual inheritance used for?

## 102. How can the diamond problem be solved without using virtual inheritance?

## 103. What will happen if a derived class is passed by value to a function that takes a base class?

## 104. What will happen if a base class with no virtual constructor is inherited from?

## 105. What will happen if a virtual function is called from a constructor? Can a constructor be virtual?

## 106. Can a pure virtual function have an implementation? What will happen if a pure virtual function is called from a constructor?

## 107. What methods are generated for a class by default? In what cases will these methods not be generated? How can you make a compiler add/remove these methods?

## 108. How can you prevent a class from being inherited from?

## 109. What is the order of constructing and destructing classes in the hierarchy? What is the order of initialization of the class fields?

## 110. What are the ways to initialize class fields?

## 111. Can a destructor be virtual?

## 112. What does the keyword virtual do?

## 113. What is a virtual destructor used for?

## 114. What is deep copying?

## 115. What are virtual functions and what are they used for?

## 116. How can an object be protected from copying?

## 117. What is move semantics?
