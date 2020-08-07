

The goal of software architecture is to minimize the work requoted to build and maintain software.

The Signature Of A Mess
The software maintenance cost increases per line of code when code cleanliness or design structure is not 

Chapter 1
When software is built without good architecture or clean code, then the cost to maintain it increases per line of code. Building software with clean architecture helps developers to minimize the effort needed to maintain and continuously rework code. Good architecture also helps to reduce the effort need to maintain and redesign the code. It also helps maximize our productivity by decreasing the amount of time and money needed to support software throughout the lifetime of the product.

Chapter 2
Software has two values to the stakeholder : 
Behaviour
Architecture
It must be easy to change. The difficulty in changing software should be proportional to the scope of the change. When architectural considerations are last, changes are impossible to make.

Software Paradigms
Software paradigms tell us what programming structures to use and when to use it
Structured Programming
Object-Oriented Programming 
Functional Programming


Each of the paradigms listed above assists in some way to modify the behaviour of the programmer. 
These paradigms modify the behaviour of the programmer removing something from them.

1938 Alan Turing laid the foundation for computer programming by first understanding that programs are just data


1938 Alan Turing laid the foundation for computer programming by first understanding that programs are just data





1951 Grace Hopper invents AO the first compiler
1953 Fortran was invented

Structured Programming

1968 Edsger Wybe Dijkstra showed that unrestrained jumps (in the form of go-to statements) are harmful. 

He discovered that programming is tough and that programmers did not do programming very well. Programs he found have a lot of complexity for the brain to handle without help, and overlooking details can result in programs that fail.
Dijkstra applied mathematical proofs, and he dreamt of a Euclidean Hierarchy. He imagined of programmers using proven structures and then tying them together.
Dijkstra found that proving theory this with basic algorithms was very challenging
He discovered that certain goto statements prevented modules from being broken down continuously into smaller modules. This prevented the use of divide and conquer proofs. He also found that good uses of goto corresponded to [if/then/else/do/while] modules and that this can then be broken down into other units.
[if/then/else/do/while] is the minimum amount of control structures that are needed for a program to be built
Dijkstra also proved that sequential statements can be proved correct through enumeration.He proved iteration by induction. He proved the case for 1 by enumeration. He proved that if N is correct, then N + 1 is also correct

Functional Decomposition 

Structured Programming allows modules to be recursively browse down into provable units

No Formal Proofs. 
Euclidean Hierarchy of Theorems never came, and programmers never saw the benefit of proving Dijkstra's theory correct. 
The scientific method 
Theories + Laws can not be proven correct 
Falsifiable but not provable 
It works by proving methods false

Tests  
A program can only be proven incorrect by a test but never correct
We show correctness by failing to prove incorrectness to a provable paradigm
We show correctness by failing to prove incorrectness to a provable paradigm 
Tests can be made to prove small provable functions incorrect.

The ability of structured programming to create falsifiable by employing disciplines similar to functional programming









