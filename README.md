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

Polymorphism is a process of performing a single action with different ways. There are 2 types of this.

Static Polymorphism: The behaviour of the class is clear in compile time. Method overload is one example to that. 
Dynamic Polymorphism: The behaviour of the class is clear in runtime. Method override is one example to that.

Encapsulation is a process of binding opject state and behaviour together. Making class is one example to that.

------
Question: What happens when there are 2 interfaces which have same method and the class wants to implement them
Answer: There will be no problems. The method with will be Override equal, so it only needs to be implemented once.

----
Final keyword

In Java classes, methods and variables can be final. Final class means it cannot be subclassed. Final variable means it can only be initialized once. Final method means the function cannot be overriden.

----



