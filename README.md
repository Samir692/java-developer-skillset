Fundamental skills for Java developers

Variable increments:

Difference between ++x and x++

++x is prefix | preincrement  | first increment then return
x++ is suffix | postincrement | first return then increment

Example

int x = 4;
int a = ++x;
int b = x++;

System.out.println(a); // 5

System.out.println(b); // 5 because first x returns its current value which is 6. then b assigns this value 6 to itself. Only after x is incremented

-----
Object Oriented Programming (OOP):
It is programming paradigm where everything is represented as objects 

Main principles:
- Abstraction
- Inheritance
- Polymorphism
- Encapsulation

Abstraction is a process where you only show "relevant" data to the user and "hide" the unnecessary data. In Java this can be achieved through abstract classes, methods.

Inheritance is a process where one class can recieve the functionalities and behaviours of the other class. It helps to have reusable and cleaner code. In Java this can be achieved by extending other class. 

Types of Inheritance:
- Single Inheritance: where one class A extends one class B
- Multilevel Inheritance: where class A extends class B where class B extends class C
- Hierarchical Inheritance: where class A extends class B where class C extends class B as well
- Multiple Inheritance: where class A extends class B and class C




