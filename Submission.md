What do we mean by **coupling** and **cohesion** when discussing structured design?

- Coupling and cohesion are ways to show how different parts of the code interact with each other. There are different levels of coupling and cohesion. 

Ideally it is better to have low coupling. This is because coupling represents how close the relationship is between modules. If you have low coupling that means your modules are not closely linked and therefore if you have a problem in one of the modules it will impact the other module quite little.  This makes it easier to fix any bugs that may occur without having to disrupt the rest of the code.


On the other hand cohesion represent the relationship within the module. Ideally it is good to have high cohesion. There are many reasons as to why high cohesion is good, some of the reasons are: the code has a high chance of being reusable as each module has a specific purpose therefore decreasing software development time.


What is the difference between **top-down** and **bottom-up** design? Which best describes a function oriented design?

- The difference between top-down and bottom-down is how you approach a given task. In top down, you will plan out the code first and then tackle each problem step by step according to the plan. On the other hand bottom up’s approach is to tackle the smaller problems first and then build up to the main problem.  Function oriented design is bottom up as each object is defined first and then the rest of the code is compiled.

In which design methodology would a **class diagram** be most useful?

Class diagrams are most useful when working with object oriented design.  This is because class diagrams help the user structure their solution by visually understanding the relationships of the system.

What are the **four pillars of object oriented programming**? Give a single-sentence description of each.


1. Inheritance. This is when a subclass (child class) can inherit all the properties of its superclass (parent class)
2. Polymorphism. This is when an object can take on many forms. This is useful when you need to inherit and attribute but make it perform different tasks.
3. Encapsulation. This is when you protect your data so it cannot be accessed from unwanted places. In java we can declare a variable as private.
4. Abstraction. This is when you only focus on the important parts of a programme and not worry about the unnecessary details. This helps with readability.


What is the **strategy pattern**? How would its implementation differ between a functional and object oriented system?

- Strategy pattern is when  a class behaviour can change change when it is running. There might be times when you need your program to do a certain thing like multiply instead of divide (for a calculator program for example).In an object oriented system strategy pattern can be used through an interface or abstract classes. Whereas in a functional system you can implement it using specific algorithms which contain the strategy.  

Imagine your is creating a new online payment system. In order to gain maximum market share it can't be tied to a particular sector - it needs to work just as well when ordering a takeaway as when buying a new coat. Which design methodology would you suggest following? Give some justification for your decision.

- I would use the object-oriented design methodology for many reasons. Here are some:

I can use the 4 pillars of OOP which all have their benefits. Overall these pillars provide different ways to manage a problem. I can break down the problem into smaller pieces and build from there. This allows for ease of collaboration if I want to get more developers on-board. Using OOP I can make sure my code is easily readable and reusable which will in term decrease developing time.

 Another example is I can setup a shop interface which has abstract classes inside which can take care of adding items, removing items and calculating payments. If there is a problem in the calculations I can easily just navigate to the interface and start debugging from there. I can also use encapsulation to protect sensitive data as I will be working with important customer data.

OOP promotes a structured and organised way to develop code therefore this methodology can make the online payment system mountable, easy to fix and easy to add to for any future changes or updates

        
