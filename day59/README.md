# Day 59

* From AUTOSAR\_EXP\_FunctionalSafetyMeasures.pdf

Introduction (p. 6)
* AUTOSAR is not a complete safe solution

Functional Safety Mechanisms:
* Memory
* Timing
* Execution
* Exchange of Information

Functional Safety Measures:
* Traceability
* Development Measures
* Evolution of the Standard
* Safety Use Case
* Safety Extensions

Hardware Diagnostics:
* Core Test
* RAM Test

Functional Safety Mechanisms (p. 8)

Faults are grouped:
* Memory
* Timing
* Execution
* Exchange of Information

Memory Partitioning (p. 9)
* prevention of memory access violations

Memory Partitioning: Fault Models (p. 9)
* Corruption of content
* Read or write access to memory allocated to another software element
* Inconsistent data
* Stack overflow or underflow

Memory Partitioning: Description (p. 10)

Memory Partitioning: Description, Application Software (p. 10)
* C-functions are referred to as Runnables
* Runnables cannot be executed by themselves (must be assigned to executable entities of the OS)

Memory Partitioning: Description, OS Applications (p. 12)
* collections of Operating System objects (e.g. Tasks, ISRs, Schedule Tables, Counters and Alarms)

Two classes of OS-Applications: 
* Trusted OS-Applications
* Non-Trusted OS-Applications
