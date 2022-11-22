Polymorphism & Composition Homework - Quiz

Polymorphism
What does the word 'polymorphism' mean?
It is the ability for something to have multiple types/shapes.

What does it mean when we apply polymorphism to OO design? Give a simple Java example.
In Java we use this to allow our objects to have multiple classes through inheritance and interfaces.

What can we use to implement polymorphism in Java?
inheritance and interfaces.

How many 'forms' can an object take when using polymorphism?
as many as there are interfaces

Give an example of when you could use polymorphism.
If you had several objects that were child objects of an animal class, for instance; Gorilla, Horse, Parrot etc. They would inherit everything from their parent Animal class and have some unique properties of their own. However you want several to be able to fly. So you would create an IFly interface and have the relevant classes inherit it. This would mean your flying animals would be of a class Animal, Parrot/Eagle/Budgie or whatever, and of IFly. Thus you could put all the flying animals into an ArrayList if you wanted while still excluding those that can't fly that also inherit from Animal.

Composition and Aggregation
What do we mean by 'composition' in reference to object-oriented programming?
Composition is when an object is made up of other objects that won't exist without the object that is being made up.

When would you use composition? Provide a simple example in Java.
A Cake object could be made up Flour, Milk, Eggs and Sugar objects. If you were to destroy or "eat" the cake, the ingredients would be destroyed too.

Give a difference between composition and aggregation?
the difference between them is that through aggregation the objects that compose the larger object won't be destroyed upon destruction of said larger object. Because they also stand on their own.

What is/are the advantage(s) of using composition/aggregation?
It allows you build more complex objects by having objects within other objects, and allows for dryer code as each component object can contain it's own details/paramaters.

When using composition, when an object is destroyed, what happens to all the objects it is composed of?
They are destroyed also.

When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?
They remain separate.