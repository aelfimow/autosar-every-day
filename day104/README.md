# Day 104

* From AUTOSAR\_EXP\_ModeManagementGuide.pdf

Modes in the RTE (p. 11)
* `ModeMachineInstance` inside `RTE`
* states are used only internally and are not visible to the application
* `BSW` has to use modes for interaction with application

Modes in the Basic Software Scheduler (p. 12)
* instatiates a `ModeMachineInstance`
* `SchM_Switch` API is provided

Communication of modes (p. 12)
* Mode Switch: always initiated by Mode Managers
* Mode Request: requested by mode users
* `Mode Proxies`

Communication of modes: Mode switch (p. 12)
* communicated via `PortPrototype`s
* `mode switch interface` (which is a `PortInterface`)
* `ModeSwitchEvent`: can trigger `OnExtry`, `OnTransition` or `OnEntryRunnable`
* `RTEEvent`: can be disabled in a certain mode and prevent the execution of `ExecutableEntities`

Communication of modes: Mode Request (p. 13)
* is done via standard `SenderReceiverInterface`
* the requested mode is given by a 'VariableDataPrototype' (not by a `ModeDeclarationGroup`)
* 1:n-connection between the mode requester and the mode managers
* possible with Sender-Receiver communication
* `COM` shall use a periodic signal with signal timeout notification to `RTE`
