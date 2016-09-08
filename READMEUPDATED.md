# Lab 02 -- Chapter 01

## Define the following terms:
***
**Object-                 state or behavior (instance) of a class.

**Class-                   blueprint (code) that defines how to create an object.

**Instance-            specific realization of any object.

**Method-            a collection of statements used to manipulate (mutators) or access (assessor) information from an object. (Behaves like a function).

**Signature (or heading)-    name of the method and the type of parameter. I.e. the following signature changes the size of the instance `box` of class `Box` and does not give an output.

```

void changeSize(Box box)

```

**Parameter-            an input of the method (I.e. `box` from example above).

**Type-                defines what values the parameter is allowed to be.

**State-                set of values describing an object.

**Source code-            collection of commands that compiles to create an executable program.

**Return value-            output of a method.

**Compiler-            transforms source code into computer readable language.
***

## In Chapter 1 we have mentioned the data types int and String. Java has more predefined data types. Find out what they are and what they are used for. To do this, you can check Appendix B, or look it up in another Java book or in an online Java language manual. One such manual is at [http://download.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html](http://download.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html)

## What are the types of the following values?


* 0                 int, double, float

* "hello"           String

* 101               int, double, float

* -1                int, double, float

* true              boolean

* "33"              String

* 3.1415            double, float




## What would you have to do to add a new field, for example one called name, to a circle object?


```

private String name;

```






## Write the header for a method named send that has one parameter of type String, and does not return a value.


```

public void send(String var1)

```



## Write the header for a method called average that has two parameters, both of type int, and returns an int value.


```

public int average(int v1,int v2)

```



## Look at the book you are reading right now. Is it an object or a class? If it is a class, name some objects. If it is an object, name its class.


The book is an object of class Books.

Or the book is a class called BluJBook and the objects are different copies of the book.



## Can an object have several different classes? Discuss.


An object can be referenced from many classes as long as it is imported.

General thought Question.
