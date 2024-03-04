# Day 36

* From AUTOSAR\_EXP\_BSWDistributionGuide.pdf

Using Shared Buffers (in systems without memory protection) (p. 14)
* protect by `ExclusiveAreas`, implemented by protected Spinlocks
* `RteExclusiveAreaImplMechanism` = `OS_SPINLOCK`

Concurrency safe implementation of modules (p. 16)
* attribute `reentrancyLevel`
* Multi-core reentrant
* Single-core reentrant
* Non-reentrant

Kernel based Master-Satellite realization (p. 17)
