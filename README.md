Polymorphism & Composition Homework - Quiz


Polymorphism

What does the word 'polymorphism' mean?
Polymorphism is when an object can be identified as another class or type at the same time as its current type.

What does it mean when we apply polymorphism to OO design? Give a simple Java example.
It means that we can identify a class as another type. Eg we could have an IVehicle interface and the Car object implement it and then the Car object can be identified as type IVehicle.  

What can we use to implement polymorphism in Java?
Interfaces, Method overloading, Method overriding.

How many 'forms' can an object take when using polymorphism?
As many interface types as the object implements plus its own type.

Give an example of when you could use polymorphism.
If you wanted to add two different types of objects to the same AssayList you could implement the same interface in both and use the interface type to add them to the ArrayList.


Composition and Aggregation

What do we mean by 'composition' in reference to object-oriented programming?
When an object is composed of other objects

When would you use composition? Provide a simple example in Java.
Adding a Roof object as part of a House object (Roof being part of the composition of House).

Give a difference between composition and aggregation?
Composition is when an object is made up of other objects being made inside it. 
Aggregation is when an object is made up of external objects that exist independantly.

What is/are the advantage(s) of using composition/aggregation?
Inheritance breaks encapsulation
Usually less classes

When using composition, when an object is destroyed, what happens to all the objects it is composed of?
They are also destroyed

When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?
Nothing as they are their own objects.
