# General questions

## Table of content

1. [General principles of OOP](#1-general-principles-of-oop)
2. [What is the Complexity of Algorithms](#2-what-is-the-complexity-of-algorithms)
3. [What if code is working incorrectly?](#3-what-if-code-is-working-incorrectly)
4. [What are the Stack and Queue?](#4-what-are-the-stack-and-queue)
5. [What names of the Programming Books have you read?](#5-what-names-of-the-programming-books-have-you-read)
6. [New features in C++17 and C++20](#6-new-features-in-c17-and-c20)
7. [What is the ASCII table?](#7-what-is-the-ascii-table)
8. [What is Unicode?](#8-what-is-unicode)
9. [What are design patterns?](#9-what-are-design-patterns)
10. [What are the Singleton, Strategy, Template-Method, and Decorator?](#10-what-are-the-singleton-strategy-template-method-and-decorator)
11. [What are modular tests for?](#11-what-are-modular-tests-for)
12. [What is the difference between Modular and Integration tests?](#12-what-is-the-difference-between-modular-and-integration-tests)
13. [What is TDD?](#13-what-is-tdd)

## 1. General principles of OOP

**Object-oriented programming *(OOP)*** is a programming [*paradigm**](#Footnotes) based on concept of [*objects**](#Footnotes),
which can contain data and code. The *data* is in the form of fields (often known as attributes or properties),
and the *code* is in the form of prodecures (often known as methods).

Many of the most widely used programming languages are multi-paradigm and they support Object-oriented programming to a greater or lesser degree,
typically in combination with *imperative* and *procedural programming*.

#### Main principles

1. **Encapsulation.** This is principle states that all important information is contained inside an object and only select (public) information is exposed.
    The implementation and state of each object are privetly help inside a defined class. Other objects do not have access to this class or the
    authority to make changes. The are only able to call a list of public functions or methods.
2. **Abstraction.** Objects only reveal internal mechanisms that are relevant for the use of other objects, hiding any unnecessary implementation code.
    The derived class can have its functionality extended.
3. **Inheritance.** Classes can reuse code from other classes. Relationships and subclasses between object can be assigned, enabling developers to reuse
    common login while still maintaining a unique hierarchy.
4. **Polumorphism.** Objects are designed to share behaviors and they can take on more than one form. The program will detemine which meaning or usage is
    necessary for each execution of that object form a parent class, reducing the need to duplicate code. A child class is then created, which extends the
    functionality of the parent class. Polumorphism allows different types of objects to pass throught the same interface.

## 2. What is the complexity of algorithms?

**The complexity of an algorithm** depends on the specific algorithm and it is implementation. Generally, algorithms are classified by their time complexity
(how long it takes to run an algorithm) and space complexity (memory requirements of the algorithm). The complexity of an algorithm is typically denoted using
*big-O notation*, which is a way of expressing the upper bound of an algorithm's running time. Big-O notation describes the complexity of an algorithm in terms
of the number of operations it needs to perform. For example, an algorithm with a complexity of **O(n)** means that it will take `n` operations to complete.

#### Types of an algorithm complexity

* **O(1):** Accessing a particular element in an collection, which requires only one operation.
* **O(log n):** Binary search algorithm, which is more efficient that linear search by dividing the list in half with each iteration. 
* **O(n):** Linear search algorithm, which compares each item in a list with the item being searched for.
* **O(n + 1):** Bubble sort algorithm, which compares adjacent items and swap them if they are out of order.
* **O(n + n):** Insertion sort algorithm, which inserts each item into it is correct position in the list.
* **O(n * n):** Quicksort algorithm, which divides the list into two partitions and recursively sorts each partition.
* **O(n ^ 2):** Selection sort algorithm, which loops throught the list to find the minimum item and swap it with the current item.

## 3. What if code is working incorrectly?

#### If my code is working incorrectly I will

1. **Check the code:** Review my code to make sure that the logic is correct and that I am not inadvertenly introducing any bugs.
2. **Use a Debugger:** Use a debugger to step throught my code and pinpoint the exact line where the issue is occuring.
3. **Use a Memory Profiler:** Use a memory profiler to check for the memory leaks and other issues that can cause incorrect behavior.
4. **Use Logs:** Logging can help me understand the path of my code and the values of variables at each step.
5. **Test my code:** Test my code with different input to ensure that it is behaving as expected.
* ***Run the Programm in a different environment:** Maybe it may help to investigate the problem to try to run the programm on different version of
Linux/Windows/MacOS.*

## 4. What are the Stack and Queue?

#### Stack

A **Stack** is a data structure that stores data in a `Last In First Out (LIFO)` format. This means that the last item added to the stack will be
the first item removed. The main advantage of a stack is that it is easy to implement and requires less memory compared to a queue. A stack
also provides faster access to the most recently added item, compared to queue.

#### Queue

A **Queue** is a data structure that store data in a `First In First Out (FIFO)` format. This means that the first item added to the queue will be
the first item removed. The main advantage of a queue is thst is allows for more complex operations than a stack, suck as adding and removing
multiple items in a single operation.

The main difference between a stack and queue is the order in which items are removed form the data structure and complexity of each other.

## 5. What names of the Programming Books have you read?

1. The C++ Programming Language - *Bjarne Stroustrup*
2. The C++ Programming Language - *Stephen Prata*

## 6. New features in C++17 and C++20

#### Features of the C++17

1. Structured bindings
2. If statements with initializer
3. Fold Expressions
4. Inline Variables
5. Template Argument Deduction
6. constexpr if
7. std::any
8. std::optional
9. std::variant
10. std::string_view
11. Parallel Algorithms

#### Features of the C++20

1. Concepts
2. Coroutines
3. Modules
4. Ranges
5. Three-way Comparison
6. Atomic Smart Pointers
7. Designated Initializers
8. Memory Model for Concurrency
9. std::format
10. std::span
11. std::bit_cast

## 7. What is the ASCII table?

The **ASCII** table is a table which contains codes for characters that can be used in text-based systems such as computers. It stands for American Standard Code for
Information Interchange and contains 128 characters, including upper and lowercase letters, numbers, symbols, and special characters. It is the most widely
used character encoding system.

## 8. What is Unicode?

The **Unicode** is a computing industry standard for the most consistent encoding, representation, and handling of text expressed in most of the world's writing
systems. It was created in 1991 and is maintained by Unicode Consortium. It is goal is to enable people around the world to use computers in any languages.

## 9. What are design patterns?

#### Design patterns

**Design patterns** are reusable solutions to common problems in software design. The provide a way to structure code in a reusable, adaptive and
maintainable way. Design patterns are used to simplify the design process and make code more efficient. The are often used to solve specific
problem in an Object-oriented programming language.

#### Types of the design patterns

1. **Creational Patterns:** *Factory Method, Abstract Factory, Singleton, Builder, Prototype*
2. **Structural Patterns:** *Adapter, Bridge, Composite, Decorator, Facade, Flyweight, Proxy*
3. **Behavioral Patterns:** *Chain of Responsibility, Command, Interpreter, Iterator, Mediator, Memento, Observer, State, Strategy, Template Method, Visitor*

## 10. What are the Singleton, Strategy, Template-Method, and Decorator?

#### Singleton

A **Singleton** is a design pattern in which an object is instantiated only once, and all subsequent requests for the object return the same instance.

```cpp
class Singleton {
private:
    static Singleton* instance;

protected:
    Singleton() {};

public:
    static Singleton* getInstance();
};

// Get the only object available
Singleton* Singleton::getInstance() {
    if (instance == nullptr)
        instance = new Singleton();

    return instance;
}
```

#### Strategy

The **Strategy** pattern is a behavioral design pattern that enables an algorithm's behavior to be selected at runtime.

```cpp
class Strategy {
public:
    virtual int execute(int a, int b) = 0;
};

// Add class
class Add : public Strategy {
public:
    int execute(int a, int b) {
        std::cout << "Called Add's execute()" << std::endl;
        return a + b;
    }
};
```

#### Template-Method

The **Template-Method** pattern is a behavioral design pattern that defines the skeleton of an algorithm in the superclass but lets subclasses
override specific steps of the algorithm without chaning its overall structure.

```cpp
class Template {
public:
    // Template method
    void sort(int arr[], int n) {
        for (int i = 0; i < n; i++) {
            for (int j = 0; j < n - i - 1; j++) {
                if (compare(arr[j], arr[j + 1]) > 0) {
                    int temp = arr[j];
                    arr[j] = arr[j + 1];
                    arr[j + 1] = temp;
                }
            }
        }
    }

    // Hook method
    virtual int compare(int a, int b) {
        return 0;
    }
};
```

#### Decorator

The **Decorator** pattern is a structural design pattern that allows behavior to be added to an existing object dynamically. It uses composition to extend the functionality
of an object without using inheritance.

```cpp
class Component {
public:
    virtual void operation() = 0;
};

class ConcreteComponent : public Component {
public:
    void operation() {
        std::cout << "ConcreteComponent operation" << std::endl;
    }
};

class Decorator : public Component {
private:
    Component *component;

public:
    Decorator(Component *c) {
        this->component = c;
    }

    void operation() {
        if (component != nullptr)
            component->operation();
    }
};
```

## 11. What are modular tests for?

## 12. What is the difference between Modular and Integration tests?

## 13. What is TDD?

## Footnotes

1. **General principles of OOP:**
    * ***Programming paradigm*** are a way to classify programming languages based on their features. Languages can be classified into multiple paradigms.
    * ***Objects*** can be a variable, a data structure, a function, or a method. As regions of memory, they contain value and are referenced by identifiers.
