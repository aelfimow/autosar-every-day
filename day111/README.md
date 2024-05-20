# Day 111

* From AUTOSAR\_EXP\_ModeManagementGuide.pdf

Communication Management: Startup and Shutdown (p. 39)

Communication Management: Partial Network Cluster (p. 39)
* `PNC`: (logical) group of ECUs which have to be active at the same time to realize some distributed functionality
* each `PNC` has its own state
* `PNC` bit vector: exchanged status of all `PNC`s on the nodes of a system channel
* `EIRA`
* `ERA`
* `IRA`

Partial Network Cluster: Aggregation of internal and external Partial Network Cluster (p. 41)
* `PN` filter mask
* `PNC` reset timer

Partial Network Cluster: Aggregation of external Partial Network Cluster (p. 41)

Partial Network Cluster: Synchronized PNC shutdown (p. 42)
* `PNC` shall shutdown in a synchronized way
* all nodes in the PNC will shutdown at the same point in time
* `Nm_ForwardSynchronizedPncShutdown`
* `ComM_Nm_ForwardSynchronizedPncShutdown`

Communication Management: Scheduling of main functions (p. 42)
