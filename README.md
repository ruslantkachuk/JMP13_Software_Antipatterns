Software Antipatterns
-----------------------

#### Coding by exception
Coding by exception is an accidental complexity in a software system in which the program handles specific errors that arise with unique exceptions. When an issue arises in a software system, an error is raised tracing the issue back to where it was caught and then where that problem came from, if applicable. Exceptions can be used to handle the error while the program is running and avoid crashing the system. Exceptions should be generalized and cover numerous errors that arise. Using these exceptions to handle specific errors that arise to continue the program is called coding by exception. This anti-pattern can quickly degrade software in performance and maintainability. Executing code even after the exception is raised resembles the goto method in many software languages, which is also considered poor practice.

#### Yo-yo problem
In software development, the yo-yo problem is an anti-pattern that occurs when a programmer has to read and understand a program whose inheritance graph is so long and complicated that the programmer has to keep flipping between many different class definitions in order to follow the control flow of the program. It often happens in object-oriented programming. The term comes from comparing the bouncing attention of the programmer to the up-down movement of a toy yo-yo. Taenzer, Ganti, and Podar described the problem by name, explaining: "Often we get the feeling of riding a yoyo when we try to understand one these message trees.

#### Circle-ellipse problem
The circle-ellipse problem in software development (sometimes termed the square-rectangle problem) illustrates several pitfalls which can arise when using subtype polymorphism in object modelling. The issues are most commonly encountered when using object-oriented programming (OOP). By definition, this problem is a violation of the Liskov substitution principle, which occurs in the term single responsibility, open-closed, Liskov substitution, interface segregation and dependency inversion (SOLID).The problem concerns which subtyping or inheritance relationship should exist between classes which represent circles and ellipses (or, similarly, squares and rectangles). More generally, the problem illustrates the difficulties which can occur when a base class contains methods which mutate an object in a manner which may invalidate a (stronger) invariant found in a derived class, causing the Liskov substitution principle to be violated.

#### God class
In object-oriented programming, a God object is an object that knows too much or does too much. The God object is an example of an anti-pattern. A common programming technique is to separate a large problem into several smaller problems (a divide and conquer strategy) and create solutions for each of them. Once the smaller problems are solved, the big problem as a whole has been solved. Therefore a given object for a small problem need only know about itself. Likewise, there is only one set of problems an object needs to solve: its own problems.

#### Dead code (Lava Flow)
In computer programming jargon, lava flow is a problem in which computer code written under sub-optimal conditions is put into production and added to while still in a developmental state. Often, putting the system into production results in a need to maintain backward compatibility (as many additional components now depend on it) with the original, incomplete design.
Changes in the development team working on a project often exacerbate lava flows. As workers cycle in and out of the project, knowledge of the purpose of aspects of the system can be lost. Rather than clean up these pieces, subsequent workers work around them, increasing the complexity and mess of the system.

#### Feature creep
Feature creep, creeping featurism or featuritis is the ongoing expansion or addition of new features in a product, especially in computer software and consumer and business electronics. These extra features go beyond the basic function of the product and can result in software bloat and over-complication, rather than simple design.

#### Feature creep
Feature creep, creeping featurism or featuritis is the ongoing expansion or addition of new features in a product, especially in computer software and consumer and business electronics. These extra features go beyond the basic function of the product and can result in software bloat and over-complication, rather than simple design.
