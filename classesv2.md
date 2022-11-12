#sample UML diagram for CSC102 by Stace Dixon<br>
#stadixon@uat.edu

Create a diagram with 2 classes. Those classes need 3 attributes, 3 methods. 

```mermaid
    classDiagram
    class Rocketship{
        -String manufacturer
        -String engineType
        -int parachutes
        +bool manned (String name)
        +testLaunch(String name)
        +bool crash(String name)
        
    }

    class Engine{
        -String type
        -String thrust
        -int exhaustVelocity
        +bool regenerativeCooling (String name)
        +testEngine()
        +launchEngine(String name)
    }