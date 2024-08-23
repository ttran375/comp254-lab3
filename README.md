# Week 11 Lab Exercises

## Exercise 1: UnsortedTableMap

Add a main method to the UnsortedTableMap class from Lesson10Examples.

Create an unsorted map of integers. Populate the map with several
entries and perform some lookups as well as *put* and *remove*
operations. Display the results.

## Exercise 2: SortedTableMap

Add a main method to the SortedTableMap class from Lesson10Examples.

Create a sorted map of Strings. Populate the map with several entries
and perform some lookups as well as *put* and *remove* operations.
Display the results.

## Exercise 3: Hash Functions

In this exercise you will create a simple hash function. The first step
is creating *h1* method that returns the hash code of an object key
(**public** **static** **int** h1(Object key)). The second step is
creating a *h2* method that returns the hash value (**public**
**static** **int** h2(**int** hashCode, **int** N).

Create a class Student that declares the instance variables
*studentNumber* and *studentName*, both of *String* type. Provide the
necessary constructors and getters/setters.

In method *h1*, use the *hashCode (Object o)* from Java to return the
hash code of an object. In method *h2*, use the division technique to
obtain the hash value ( = hashCode % N) .

Write a main method to test your solution. Create a Student object. Use
h1 method to compute the hashcode for the student object, the h2 method
to compute the hash value. Choose N to be a prime number (try 109, etc).

## Exercise 4: Separate Chaining

Draw the 9-entry hash table that results from using the hash function,
h(i) = (2i + 5) mod 9, to hash the keys 13, 12, 44, 88, 23, 94, 11, 39,
20, assuming collisions are handled by separate chaining technique.

## Exercise 5: Linear Probing

For the table in Exercise 4, repeat the same assuming that collisions
are handled using linear probing.

## Exercise 6: Sets

java.util.HashSet provides an implementation of the (unordered) set ADT
with a hash table.

Write a main method that creates a set of objects and perform the basic
set operations. Iterate over set elements and print their values.
