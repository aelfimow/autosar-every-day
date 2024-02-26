# Day 29

* From AUTOSAR\_EXP\_CDDDesignAndIntegrationGuideline.pdf

* `ComplexDeviceDriverSwComponentType`
* `RunnableEntities`
* `SwcInternalBehavior`

Hints: (p. 15)
* Server runnables is prefered to be re-entrant (can be invoked concurently = TRUE)
* Runnables signature to be:
```
void RunnableName(void or parameters)
```
or
```
StdReturnType RunnableName(void or parameters)
```

Interfacing to standard BSW modules (p. 17)
