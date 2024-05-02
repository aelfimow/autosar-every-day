# Day 93

* From AUTOSAR\_EXP\_VFB.pdf

Sender-Receiver communication: Filtering between the sender and the receiver (p. 57)
* filter can only be specified on the receiving side

Specification items (p. 57)
* `EXP_Vfb_00027`
* `EXP_Vfb_00028`

Sender-Receiver communication: Concurrency and ordering within a sender-receiver connector (p. 57)
* does not guarantee any ordering between changes to different data elements
* does not guarantee any ordering between mode switches of different `ModeDeclarationGroups`

Specification items (p. 58)
* `EXP_Vfb_00029`

Client-Server communication (p. 58)
* static n:1 client-server mechanism

Specification items (p. 60)
* `EXP_Vfb_00031`

Client-Server communication: From the point of view of the client (p. 61)
* good rule: make the operation `idempotent` (can be repeated an arbitrary number of times)
* attribute `CLIENT_MODE` (synchronous, asynchronous and `wakeup_of_wait_point`, asynchronous and `activation_of_runnable entity`)
* attribute `TIMEOUT`

Specification items (p. 61)
* `EXP_Vfb_00032`
* `EXP_Vfb_00033`
* `EXP_Vfb_00034`
* `EXP_Vfb_00035`
* `EXP_Vfb_00036`
* `EXP_Vfb_00037`
* `EXP_Vfb_00038`

Client-Server communication: From the point of view of the server (p. 62)
