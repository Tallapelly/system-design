# System design

What is system design? [link](https://www.youtube.com/watchv=SqcXvc3ZmRU 'sd')
- It is main like creating an architechture for different componets     or modules and to provide corresponding data helpul in implementation.
-There  are a lot of things to know in system design like how to optimise and we will be learnign about horizontal scaling and vertical scaling ,load balancer 

***
### Low Level Design(LLD)

- LLD refer to the design of the small components of an application that serves the requirement .
- requirement Gathering
- Laying down use cases
- UML/Class diagrams (uml is not a programming language but a visual language we use UML to potray the behaviour or structure of the system)
- OOD to model the programs

** The main motive of the LLD is use to convert the class diagram to actual code usign oops **
 
 We should also keep in mind that our code is  testable ,maintanable refactored ready which is production ready and it is ready for changes also or ready extension

### Basics of objects and classes

What are objects and classes?
-Object  comprises of two things *Information* which we call data or attributes *behaviour* it is the property of the object

-Classes as the text book defination everyone know is the blueprint of objects or blueprint of object

Taking a real world example we are creating a class called car so in that class we have different data like wheel,door,tyres so this is our class car from using this information we will build different cars which have different values it reduces huge amount of code.

#### Noun Verb Technique

what is nvt technique?
-(Noun)It is main like when we get a real world probleem scenario or you can say a problem statement in that first identify all the nouns and those nouns are your *classes* or you can say *domain classes*

-(Verb) in the problem statement you can see the verb these verbs make up the behaviour of the classes they give you the idea how many classes should be used and relation between two classes.

For example below the test case 
![image](https://github.com/adam-p/markdown-here/assets/111244831/9f75f7a1-0bfb-4fc2-86ed-5799c692c34b)
This are the divided classes based on the given test cases=
![image](https://github.com/adam-p/markdown-here/assets/111244831/2a32a6ee-b1ec-4496-af82-f6f53e9826b6)


Like their are two types of relations betweem classes 

1.Composition
2.Aggregation
-These both come under *has a relation* type
    Compostion:- If a class is completely depended on another class like we can say their is no use of a classA if classB doesn't exist this type of relationship is called compositon

    Aggregation- It is vice-versa to compostion

- Another is the *is a relation*    

*Hiding of the data is called **Abstraction** *
*Implementaion of Abstraction id called **encapsulation** *

### Solid Principles

#### (s) Single Responsibility Principle (SRP)
- If any class had only 1 actor to request the change in the class obeys SRP . If it has multiple actors it doesn't obey SRP

- To solve this issue we have to break our class into multiple classes