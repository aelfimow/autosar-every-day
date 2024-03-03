# Day 35

* From AUTOSAR\_EXP\_BSWDistributionGuide.pdf

Core-Dependent Branching (p. 11)
* `GetCoreID`
* `GetApplicationID`

Master/Satellite-approach (p. 11)
* Always vendor specific solution
* The communication between master and satellites is not standardized
* Standard solution for system services in partitioned systems: master/satellite implementation

Using the BSW Scheduler for Inter-Partition-Communication (p. 13)

Case 1: for synchronous calls
```
Std_ReturnType SchM_Call_<bsnp>[_<vi>_<ai>]_<name>(
    [OUT <typeOfReturnValue> returnValue]
    [IN|IN/OUT\|OUT]<data_1> ... [IN|IN/OUT|OUT] <data_n>)
```

Case 2: for asynchronous calls
```
Std_ReturnType SchM_Call_<bsnp>[_<vi>_<ai>]_<name>(
    [IN|IN/OUT\|OUT]<data_1> ... [IN|IN/OUT|OUT] <data_n>)
```

Callback from an asynchronous client-server-operation:
```
Std_ReturnType SchM_Result_<bsnp>[_<vi>_<ai>]_<name>(
    [IN|IN/OUT|OUT]<data_1> ... [IN|IN/OUT|OUT] <data_n>)
```

Send/Receive data:
```
Std_ReturnType SchM_Send_<bsnp>[_<vi>_<ai>]_<name>(IN <data>)
Std_ReturnType SchM_Receive_<bsnp>[_<vi>_<ai>]_<name>(OUT <data>)
```

Using Shared Buffers (in systems without memory protection) (p. 14)
