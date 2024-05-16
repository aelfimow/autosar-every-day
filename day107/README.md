# Day 107

* From AUTOSAR\_EXP\_ModeManagementGuide.pdf

Configuration of the Basic Software Modemanager (p. 17)
* Implements the part of the Vehicle Mode Management and Application Mode Management concept that resides in the BSW
* The configuration of the `BswM` is very project- and ECU- specific

Process how to configure and integrate a `BswM` (p. 17)

Semantics of BswM Configuration: Interfaces and behavioral aspects (p. 18)
* `BswMModeRequestSource`: each mode request is described in the ECU configuration

Interface of the BswM (p. 18)
* `BswMModeRequestSource`
* `BswMActionListItem`

Interface of the BswM: Mode Requests (p. 18)
* `BswMModeRequestSource` is a `ChoiceContainer`
* `SchM_Switch`

Interface of the `BswM`: Available Actions (p. 19)

Definition of the interface in pseudo code (p. 20)
