# Design pattern 

### 1 Strategy Pattern

> - "Gang of Four " ==> 4 authors of the book *Design Patterns: Elements of Reusable Object-Oriented Software*

:blush:Design Principles —— Indentify the aspects of your application that vary and seperate them from what stays the same.

- Encapsulate what varies
- Program to an interface, not to an implementation
- Favor composition over inheritance

:wink:Liskov Substitution Principle —— Let q(x) be a property provable about objects x of type T. Then q(y) should be provable for objects y of type S where S is a subtype of T.

---

SimUDuck Example:

- Different ducks **extends** Duck;

- Duck **has-a** FlyBehavior and QuackBehavior;
- Specific behaviors **implements** FlyBehavior and QuackBehavior.

![image-20181225173503775](./img/image-20181225173503775.png)



### 2 Observer Pattern

![image-20181227095721757](/Users/wangyutong/Library/Application Support/typora-user-images/image-20181227095721757.png)

vs. java 内置的观察者模式

![image-20181227100418852](/Users/wangyutong/Library/Application Support/typora-user-images/image-20181227100418852.png)


