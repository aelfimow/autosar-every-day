# Day 106

* From AUTOSAR\_EXP\_ModeManagementGuide.pdf

Communication of modes: Mode proxies (p. 14)
* Constraint: only local software components are allowed to communicate with `ServiceComponents`
* `ServiceProxySwComponentType`
* `ServiceProxySwComponentType` can only receive but not send signals over the network

Figure: Communication via `ServiceProxySwComponents` (p. 15)

Communication of modes: Mode communication on multi core ECUs (p. 15)
* `ModeUsers` of a `ModeDeclarationGroup` prototype can be distributed on several partitions
* 10 steps during a mode transition
* `modeManagerErrorBehavior.errorReactionPolicy`, `lastMode`

Configuration of the Basic Software Modemanager (p. 17)
