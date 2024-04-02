# Day 63

* From AUTOSAR\_EXP\_FunctionalSafetyMeasures.pdf

Timing Monitoring: Fault Models (p. 24)
* Blocking of execution
* Deadlocks
* Livelocks
* Incorrect allocation of execution time
* Incorrect synchronization between software elements

Timing Monitoring: Description (p. 25)

Timing Monitoring: Description, Supervised Entities (p. 25)
* logical units of supervision
* Checkpoints

Timing Monitoring: Description, Watchdog Manager (p. 25)
* Alive Supervision
* single Checkpoint without transitions
* Deadline Supervision

Timing Monitoring: Description, Timing Protection of the Operating System (p. 27)
* Execution Time Protection
* Execution Budget: Upper bound for execution time of Tasks or Cat2 Interrupts
* Locking Time Protection
* Lock Budget: Upper bound for blocking of resources, locking and suspending of interrupts
* Inter-Arrival Time Protection
* Time Frame: Lower bound between tasks being activated or Cat2 Interrupts arriving

Cat1 Interrupts: Category 1 Interrupts
* executed outside of the Operating System

Cat2 Interrupts: Category 2 Interrupts
* managed by the Operating System

Timing Monitoring: Description, Detection and Reaction (p. 28)
* Deadline Supervision
* Alive Supervision
* Logical Supervision
* configured statically
* Local Status: status of the Supervised Entity
* Global Supervision Status: status of the whole MCU

Recovery mechanisms:
* Error Handling in the Supervised Entity
* Partition Shutdown
* Reset by Hardware Watchdog
* Immediate MCU Reset
