# Day 190

* From AUTOSAR\_EXP\_InterruptHandlingExplanation.pdf

Handling `cat1` interrupts: Initial state (p. 11)
* target-specific

Handling `cat1` interrupts: When the hardware requests an interrupt (p. 11)

Handling `cat2` interrupts: Initial state (p. 13)
* `cat2`: much higher level of abstraction than `cat1` interrupts
```
ISR(Can_tx) {
    ...
}
```

Handling `cat2` interrupts: When the hardware requests an interrupt (p. 13)

Configuration of Interrupts (p. 15)

Configuration of Interrupts: Device Driver configuration and code (p. 15)
* `Cat1` interrupt handlers: do not have `OS` support

Configuration of Interrupts: Placement of Interrupt Handlers (p. 16)
