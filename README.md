# execption_lambda_interface

       **  execption  **

1. Explain different types of Errors in java.
 Ans :   Runtime Error
        Compile Time Error

2. What is an Exception in java .
 Ans : Formally, an exception in Java is “an event, which occurs during the execution of a program, that disrupts the normal flow of the program's instructions.”
   There are many typical causes for exceptions in Java, including: Loss of network connectivity. Invalid input data. Requests for missing or non-existent files.

3. How can you handle exceptions in java?Explain with an example .
 Ans : The Exception Handling in Java is one of the powerful mechanism to handle the runtime errors so that the normal flow of the application can be maintained.
   In this tutorial, we will learn about Java exceptions, it's types, and the difference between checked and unchecked exceptions.

4. Why do we need exception handling in java?
 Ans : Exception handling is the process of responding to unwanted or unexpected events when a computer program runs.
    Exception handling deals with these events to avoid the program or system crashing, and without this process, exceptions would disrupt the normal operation of a program.

5. What is the difference between exception and error in java?
 Ans : Both exceptions and errors are the subclasses of a throwable class. The error implies a problem that mostly arises due to the shortage of system resources.
 On the other hand, the exceptions occur during runtime and compile time.
   
6. Name the different types of exceptions in Java.
 Ans : Built-in exceptions are the exceptions that are available in Java libraries. These exceptions are suitable to explain certain error situations.
 Below is the list of important built-in exceptions in Java. 

ArithmeticException: It is thrown when an exceptional condition has occurred in an arithmetic operation.
ArrayIndexOutOfBoundsException: It is thrown to indicate that an array has been accessed with an illegal index. 
The index is either negative or greater than or equal to the size of the array.

ClassNotFoundException: This Exception is raised when we try to access a class whose definition is not found

FileNotFoundException: This Exception is raised when a file is not accessible or does not open.

IOException: It is thrown when an input-output operation failed or interrupted

InterruptedException: It is thrown when a thread is waiting, sleeping, or doing some processing, and it is interrupted.

NoSuchFieldException: It is thrown when a class does not contain the field (or variable) specified

NoSuchMethodException: It is thrown when accessing a method that is not found.

NullPointerException: This exception is raised when referring to the members of a null object. Null represents nothing

NumberFormatException: This exception is raised when a method could not convert a string into a numeric format.

RuntimeException: This represents an exception that occurs during runtime.

StringIndexOutOfBoundsException: It is thrown by String class methods to indicate that an index is either negative or greater than the size of the string

IllegalArgumentException : This exception will throw the error or error statement when the method receives an argument which is not accurately fit to the given relation or condition. It comes under the unchecked exception. 

IllegalStateException : This exception will throw an error or error message when the method is not accessed for the particular operation in the application. It comes under the unchecked exception.


              **  lambda  **

              
1. What is the lambda expression of Java 8?
 Ans :  Lambda Expressions were added in Java 8. A lambda expression is a short block of code which takes in parameters and returns a value. Lambda expressions are similar to methods, but they do not need a name and they can be implemented right in the body of a method.

2. Can you pass lambda expressions to a method? When?
 Ans : If we need to pass a lambda expression as an argument, the type of parameter receiving the lambda expression argument must be of a functional interface type.
  In the below example, the lambda expression can be passed in a method which argument's type is "TestInterface".

3. What is the functional interface in Java 8?
 Ans : An Interface that contains exactly one abstract method is known as functional interface. It can have any number of default, static methods but can contain only one abstract method. It can also declare methods of object class. Functional Interface is also known as Single Abstract Method Interfaces or SAM Interfaces.

4. What is the benefit of lambda expressions in Java 8?
 Ans :  Java has a potent tool for functional programming thanks to lambda expressions. Lambda expressions enable clear and expressive code, which improves the readability and modularity of the code.

5. Is it mandatory for a lambda expression to have parameters?
 Ans : Using Lambda Expressions
Lambda expressions can be stored in variables if the variable's type is an interface which has only one method. The lambda expression should have the same number of parameters and the same return type as that method.


               **  interface  **

 1. What is an interface in Java?
  Ans : An interface in the Java programming language is an abstract type that is used to declare a behavior that classes must implement. They are similar to protocols.
    Interfaces are declared using the interface keyword, and may only contain method signature and constant declarations.  

2. Which modifiers are allowed for methods in an Interface?Explain with an example
 Ans : Only public and abstract modifiers are allowed for methods in interfaces.

3. What is the use of interface in Java?
Ans: There are many reasons to use interfaces in java. They are as follows:
a. An interface is used to achieve full abstraction.
b. Using interfaces is the best way to expose our project’s API to some other project.
c. Programmers use interfaces to customise features of software differently for different objects.
d. By using interface, we can achieve the functionality of multiple inheritance.

4. What is the difference between abstract class and interface in Java?
5. Abstract class and interface both are used to achieve abstraction where we can declare the abstract methods. Abstract class and interface both can't be instantiated.
But there are many differences between abstract class and interface that are given below.
  ** Abstract class **	                                ** Interface **
1) Abstract class can have abstract and non-abstract methods.	        *Interface can have only abstract methods. Since Java 8, it can have default and static methods also.
2) Abstract class doesn't support multiple inheritance.	             * Interface supports multiple inheritance.
3) Abstract class can have final, non-final, static and non-static variables.*Interface has only static and final variables.
4) Abstract class can provide the implementation of interface.	       *Interface can't provide the implementation of abstract class.
5) The abstract keyword is used to declare abstract class.	            * The interface keyword is used to declare interface.
6) An abstract class can extend another Java class and implement multiple Java interfaces.	*An interface can extend another Java interface only.
7) An abstract class can be extended using keyword "extends".	    *An interface can be implemented using keyword "implements".
8) A Java abstract class can have class members like private, protected, etc.	Members of a Java interface are public by default.
