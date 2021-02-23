# Day 51
__02/22/2021__

## What does inheritance accomplish for us in C#?

Inheritance in C# can do a great deal for developers. One of the main selling points is that it can help in reducing repeating code. Each parent class shares its like information with its children. Inheritance can also signify what types things are or what they are children of.


## How does Member inheritance work in C#? Does a class inherit all members of a base class?

Almost all of the members in the parent class are transfered down to the children classes. The children all the way down the inheritance chain have access to whatever gets passed to them from their parent class.
Almost every member of a class can be inherited from the base class to the derived class. The exceptions being constructors, and finalizers. Those two things cannot be inherited from a parent to a child. 


## How does accessibility affect inheritance?

Accessability controls whether or not the members that are getting passed down are visible or not. Public methods and members are always visable and usable. On the other end of the spectrum, private classes are never visable in the children, unless they are nested inside of the parent. Then with protected members they are only visable in the child class, and with Internal members they are only visable when the derived class is located in the same assembly as the base class.


## Afternoon Project Link:

https://steffenlarson.github.io/Vacay/


## Reading: Foundations of C#: C# Inheritance