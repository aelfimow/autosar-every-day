# Day 192

* From AUTOSAR\_EXP\_InterruptHandlingExplanation.pdf

Critical sections: Critical sections in the `BSW` Scheduler (p. 20)
* Suspend/resume or enable/disable interrupts
* `RESOURCE`s

Summary (p. 20)
* configuration of the `BSW` scheduler is a problem

Recommendations for the use of `cat1` interrupts (p. 21)
* circumstance: interrupt arrival rate causes unacceptable overheads
* circumstance: interrupt latency must be so low that a `cat2` `ISR` is not fast enough
* circumstance: the defined interrupt handler requires low jitter

Communication between adjacent modules using cat1 interrupts (p. 21)
* special worry with `cat1` interrupts: Long blocking times

Trust (p. 22)
* all `cat1` interrupt handlers must be trusted.
