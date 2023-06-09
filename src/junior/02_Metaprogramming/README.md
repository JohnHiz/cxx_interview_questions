# Metaprogramming

## Table of contents

14. [What is a template class and a template function?](#14-what-is-a-template-class-and-a-template-function)
15. [What are constructors? What types do you know?](#15-what-are-constructors-what-types-do-you-know)
16. [Can a constructor be a template function?](#16-can-a-constructor-be-a-template-function)
17. [Can a virtual function be a template?](#17-can-a-virtual-function-be-a-template)
18. [What is a template instantiation?](#18-what-is-a-template-instantiation)
19. [What is a template specialization? What is a partial template specialization?](#19-what-is-a-template-specialization-what-is-a-partial-template-specialization)
20. [Tell us about the implementation of template classes in a .cpp file](#20-tell-us-about-the-implementation-of-template-classes-in-a-cpp-file)

## 14. What is a template class and a template function?

#### Template class

A template class is a generic class that serves as a blueprint for creating other classes and functions. Template classes can be used to
create type-safe and generic functions and classes.

```cpp
template <class T>
class MyClass
{
public:
    T value;

    MyClass(T val)
    {
        value = val;
    }

    T getValue()
    {
        return value;
    }
};
```

#### Template function

A template function is a function that can be used to generate a specific version of a function or class based on the input parameters.
Template functions are used to create type-safe and generic functions that can be reused with different data types.

```cpp
template <typename T>
T add(T a, T b)
{
    return a + b;
}
```

## 15. What are constructors? What types do you know?

## 16. Can a constructor be a template function?

## 17. Can a virtual function be a template?

## 18. What is a template instantiation?

## 19. What is a template specialization? What is a partial template specialization?

## 20. Tell us about the implementation of template classes in a .cpp file

## Footnotes
