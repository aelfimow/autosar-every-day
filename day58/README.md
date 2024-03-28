# Day 58

* From AUTOSAR\_EXP\_BSWDistributionGuide.pdf

Technical Terms (p. 83)

BSW functional cluster:
* A coherent group of BSW modules
* allocation of modules to clusters is currently not standardized
* may be similar to "stack" 

AUTOSAR BSW Cluster Interface

Master:
* coordinates requests by satellites
* can filter or monitor incoming satellite requests

Satellite:
* The distribution of work between master and satellite is implementation specific
* In general cannot work without the master
