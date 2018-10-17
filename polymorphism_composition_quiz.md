# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?
  A. taking many forms

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

  A. if an object has a superclass, or implements an interface, it can be referred to as an
  instance of the superclass or of the interface
//eg Java
  public interface ISleep{};
  public class Animal;
  public class Bear extends Animal implements ISleep;
a variable could be declared using Animal, Bear or ISleep, the Object would perform as each one


3. What can we use to implement polymorphism in Java?
  A. superclasses, abstract classes, interfaces

4. How many 'forms' can an object take when using polymorphism?
  A. as many as are applied

5. Give an example of when you could use polymorphism.
  A. grouping objects of different classes into an arraylist by behaviour


# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?
  A. an object being made up of other objects

7. When would you use composition? Provide a simple example in Java.
  A. when an object is required to use behaviour from other classes
 //Java
  public class Tree {
    private int height;
    public void fall(){

    }
  }
  public class Person {
    private String name;
    private int numberOfEars;
  }
  public class Forest {
    private String name;
    private int acreage;
    private Person owner;
    private Arraylist<Tree> trees;
  }

8. What is/are the advantage(s) of using composition?
  A. can utilise required behaviour without cluttering up classes with unnecessary properties etc

9. When an object is destroyed, what happens to all the objects it is composed of?
  A. they are also destroyed
