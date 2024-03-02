# Day 34

* From AUTOSAR\_EXP\_BSWDistributionGuide.pdf

BSW functional cluster (p. 9)

Example:
* IOHWA + ADC in one partition
* IOHWA + ADC + DIO in the second partition

Candidates to be standardized in a later releases:
* Communication cluster
* Memory cluster
* I/O cluster
* Watchdog cluster

Inter-BSW-partition communication (p. 10)

Determining the Partition for Service Execution (p. 10)
* Case 1: Event is mapped to a task, it is executed within the partition assigned to this task
* Case 2: Event is not mapped to a task, it is executed within the same partition as the task that caused the event

BSW partitions (p. 11)
* `EcucPartitionBswModuleExecution` = true: configuration parameter
