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

**Main principles:**
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

**Types of an algorithm complexity:**

* **O(1):** Accessing a particular element in an collection, which requires only one operation.
* **O(log n):** Binary search algorithm, which is more efficient that linear search by dividing the list in half with each iteration. 
* **O(n):** Linear search algorithm, which compares each item in a list with the item being searched for.
* **O(n + 1):** Bubble sort algorithm, which compares adjacent items and swap them if they are out of order.
* **O(n + n):** Insertion sort algorithm, which inserts each item into it is correct position in the list.
* **O(n * n):** Quicksort algorithm, which divides the list into two partitions and recursively sorts each partition.
* **O(n ^ 2):** Selection sort algorithm, which loops throught the list to find the minimum item and swap it with the current item.

## 3. What if code is working incorrectly?

## 4. What are the Stack and Queue?

## 5. What names of the Programming Books have you read?

## 6. New features in C++17 and C++20

## 7. What is the ASCII table?

## 8. What is Unicode?

## 9. What are design patterns?

## 10. What are the Singleton, Strategy, Template-Method, and Decorator?

## 11. What are modular tests for?

## 12. What is the difference between Modular and Integration tests?

## 13. What is TDD?

## Footnotes

1. **General principles of OOP:**
    * ***Programming paradigm*** are a way to classify programming languages based on their features. Languages can be classified into multiple paradigms.
    * ***Objects*** can be a variable, a data structure, a function, or a method. As regions of memory, they contain value and are referenced by identifiers.
