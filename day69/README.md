# Day 69

* From AUTOSAR\_EXP\_FunctionalSafetyMeasures.pdf

End-2-End Protection: Description, COM End-2-End Callout (p. 48)
* Each `I-PDU` has a separate callout function

End-2-End Protection: Description, RTE Data Transformer (p. 50)
* Complex data element: instance of a complex data type
* Complex data type: one or more primitive data types

End-2-End Protection: Detection and Reaction (p. 52)

End-2-End Protection: Limitations (p. 52)
* End-2-End Library alone is not sufficient to achieve a safe End-2-End communication
* The user is responsible to demonstrate that it is sufficient
* Further fault models have to be considered: 
* RTE errors in Data Conversion
* Filtering
* missing notifications
* wrong order of parameters in client-server communication
* delays in transmission
* Consider runtime-overhead
* No time stamps in the control data
