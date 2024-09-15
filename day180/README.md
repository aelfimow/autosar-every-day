# Day 180

* From AUTOSAR\_EXP\_FirmwareOverTheAir.pdf

Functional and Architectural Elements (p. 19)
* `FOTA` Target `ECU`
* `FOTA` Master `ECU`
* backend server

`FOTA` Target `ECU` (p. 19)
* `FOTA` handler module is seen as a `CDD`

Functional Description of the `FOTA` Handler Module (p. 19)
* `FOTA` chunk buffer 
* `FOTA_ProcessTransferDataWrite`
* `FOTAHandlerMain`

Diagnostics (`Dcm`) (p. 20)
* Session Handling
* Security Access
* Authentication
* Service Handling (user jobs)
* Error Handling
* Check Programming Conditions
* Reset/Restart ECU

`Nv` Data (p. 21)
