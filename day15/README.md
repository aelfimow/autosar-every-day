# Day 15

* From AUTOSAR\_EXP\_ApplicationLevelErrorHandling.pdf

Terminating and restarting partitions (p. 45)
* definition of a software partition (p. 46)
* enforcement of error containment regions

Use Case 1: Software Partitioning (p. 47)
* fail silent behaviour

Use Case 2: Application-level Error Handling (p. 48)
* `ALEM`: Application Level Error Manager

Approach for Terminating and Restarting Partitions (p. 50)

OS-Applications (p. 50), a set of:
* OS objects:
* tasks
* interrupt service routines
* alarms
* schedule tables

Protection Hook (p. 51)
* `ShutdownOS()`
* Return values:
* `PRO_IGNORE`
* `PRO_TERMINATETASK`
* `PRO_TERMINATEAPPL`
* `PRO_TERMINATEAPPL_RESTART` (a must for terminating or restarting a partition)
* `PRO_SHUTDOWN`

`TerminateApplication()` API (p. 52)

OS-Application state machine (p. 53)
* `APPLICATION_ACCESSIBLE`
* `APPLICATION_RESTARTING`
* `APPLICATION_TERMINATED`

Partition state machine (p. 55)
* `P_PREACTIVE`
* `P_ACTIVE`
* `P_TERMINATING`
* `P_TERMINATED`
* `P_RESTARTING`
