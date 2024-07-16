# Day 167

* From AUTOSAR\_EXP\_CPSwClusterDesignAndIntegrationGuideline.pdf

Design Philosophy, Goals and Non-Goals (p. 14)

Relation to `EcucPartitions` (p. 15)
* possibility to separate functions
* `OSApplication`s
* one `Software Cluster` can contain multiple `EcucPartition`s

Assumption on the applicable target `ECU`s (p. 16)
* Targets with Memory Management Units are out of scope

Assumption on safety mechanisms (p. 16)
* Assumption: Communication local to an `ECU` utilizing RAM is safe
* Assumption: Communication between `Software Clusters` on the same machine is considered as safe

Assumption on the to-be-clustered SW system (p. 16)
