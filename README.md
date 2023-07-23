# Clear Concept of Object Oriented Prgramming(OOP)

## Object Oriented Programming Basics:

+ className will be capital letter
+ There’s few properties and methods
+ Few access modifiers - public, private, protected, static
+ Can create object/instance by new className.
+ If you want to access own property in a method, have to use $this keyword.
+ If property/methods are static then no need to create an object, <br/>
+ just self/className::method_Name(:: - superscope regulation operator).
+ Encapsulation, polymorphism

## Create object: 
+ Creating a object is only and only for class
+ 1 class can extend only one class
+ Interface & abstract & trait == Object Not allowed.
+ Multiple inheritance => if you want to access so many classes

## 1) Access Modifier:

+ **Public** - possible to access any property/method from outside of a class

+ **Protected** - can't access from out of class without getting permission.

**Tricks to access**- make a public method, return the protected attribute and then call the methods by creating an object.

Means - if the protected property/method is used in a public method then it can be and you have to use $this keyword.

+ This rules also applicable for inheritance

## 2) Encapsulation- 
means to protect attributes/methods using these keywords public/private/protected/abstract/final from outside access of a class.

## 3) Constructor(Built-in Magic method)
+ Automatic called when object is created
+ No need to be called
+ () will given if it has constructor with parameter

## 4) Polymorphism (multi inheritance)-
                           allows multiple class with various functionalities to implement or share a common Interface
+ Abstract+interface+trait == polymorphism
+ Most familiar - abstract, interface, trait
+ Can override the parent class methods.
+ Parent::methodName()

**Abstract+interface => override the parent functions**

## 5) Abstract class:
+ Must include abstract keyword before class.
+ Syntax: abstract class className{}
+ Have to extend by other class
+ Property, method can be public, private, protected.
+ May have so many methods, but at least 1 abstract method
+ No need to define body in abstract method 
+ Not allowed to make object
+ Without extend you can’t access its property and methods and you can use its abstract method or not.
+ Abstract a kisu instruction thakbe ja extend korle must use kortei hobe

## 6) Interface:
+ Must include interface keyword before className(it has no class keyword).
+ As it’s not a class, so can’t use extends but implements
+ Allow to define only a few functions, nothing is allowed to its body.
+ You must have to use interface functions if you implement
+ And then override the functions. 

## Note: 
+ Abstract + Interface +trait = polymorphism
+ Interface => implements (you can implement so many interfaces)
+ Trait => use (as your wish)
## 1 Class can =>
         + extends(1 class/1 abstract),
         + implements(multiple interface), 
         + use(multiple trait), 

**Note:** Implement korlei function use kortei hobe, noile error asbe

## 7) Trait: 
+ Trait == multi inheritance, start a trait keyword thakte hobe, aker odhik extend need hole trait 
+ Vitore Use korte hoy
+ Trait class er moto, kintu class na. So, private/protected property/method access kora jabe na.

## Difference between Abstract Class and Interface 
+ **Abstract**: class is a class that cannot be instantiated and can contain both abstract and non-abstract methods.
+ **Interface**: specifies a set of methods that a class must implement.
