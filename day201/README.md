# Day 201

* From AUTOSAR\_EXP\_NVDataHandling.pdf

Use Case Summary (p. 21)

Case 1: Application `SW-C` accessing `NVRAM` Blocks having no Permanent `RAM` block (p. 21)
* Case 1a: Application providing reference to its `RAM` data area
* Case 1b: `NvM` fetches application `RAM` data via callback (`NvM` Explicit Synchronization)

Case 2: Application `SW-C` accessing `NVRAM` blocks which have Permanent `RAM` blocks (p. 30)

Case 3: Application `SW-C` accessing `NVRAM` block using an `NvBlockSwComponentType` (p. 34)
* Case 3a: Using `RTE` Explicit `S/R` Communication (p. 38)
* No Dirty Flag Support (p. 38)
* With Dirty Flag Support (p. 40)
* Storing at Shutdown (p. 41)
* Storing Immediately (p. 43)

* Case 3b: Using Rte Implicit S/R Communication (p. 45)
