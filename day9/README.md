# Day 9

* From AUTOSAR\_EXP\_LayeredSoftwareArchitecture.pdf

Configuration classes (p. 122)
* Pre-compile time
* Link time
* Post-build time

Configuration class: Pre-compile time
* `Example_cfg.h`
* `Example_cfg.c`

Variants (p. 132)
* VARIANT-PRE-COMPILE (Pre-compile time configuration allowed)
* VARIANT-LINK-TIME (Pre-compile and link time configurations allowed)
* VARIANT-POST-BUILD (Pre-compile and link and post-build time configurations allowed)

Runnables (p. 136)
* Active parts of Software Components
* Mapped to different Tasks

Partitioning (p. 138)
* OS-Applications
* `IOC` for communication across OS-Applications
* ProtectionHook
* OsRestartTask
* RTE
* Operating System
* Termination
* Error detection in applications

Scheduling (p. 144)
* Basic Software Scheduler and RTE are generated together

Mode management (p. 156)
* Mode manager in each OS-Application

