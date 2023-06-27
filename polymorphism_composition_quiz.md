# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?
Polymorphism means 'many forms'

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.
When we apply it to OOP it means we can have many classes that are related to each other by inheritance. In Java you might have an Instrument class and then sub-classes such as Guitar, Drums etc. You might have a method in Instrument called play() that can be used by the sub-classes.

3. What can we use to implement polymorphism in Java?
We can use inheritance e.g extends, abstract classes, interfaces

4. How many 'forms' can an object take when using polymorphism?
It depends on the amount of classes it belongs to or interfaces it implements? 

5. Give an example of when you could use polymorphism.
You could have a parent class called employee that has a string of name and a function to calculate salary. then you could have different child classes of something like full-time employee or part-time etc


# Composition and Aggregation

6. What do we mean by 'composition' in reference to object-oriented programming?
It is when we have objects that are composed of other objects

7. When would you use composition? Provide a simple example in Java.
You might have different classes for components of PC like GPU, CPU etc then you could have the PC class composed of the different components

8. Give a difference between composition and aggregation?
in composition the object is composed of its components. in aggregation the objects are associated but not necessarily integral. 

9. What is/are the advantage(s) of using composition/aggregation?
reuasbility, flexibility, extensibility

10. When using composition, when an object is destroyed, what happens to all the objects it is composed of?
I think in both cases the object that holds the component objects can survive regardless if they are destroyed or not. 
11. When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?