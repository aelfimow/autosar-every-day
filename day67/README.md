# Day 67

* From AUTOSAR\_EXP\_FunctionalSafetyMeasures.pdf

End-2-End Protection: Fault Models (p. 37)
* Repetition of information
* Loss of information
* Delay of information
* Insertion of information
* Masquerade or incorrect addressing of information
* Incorrect sequence of information
* Corruption of information
* Asymmetric information sent from a sender to multiple receivers
* Information from a sender received by only a subset of the receivers
* Blocking access to a communication channel

End-2-End Protection: Description (p. 38)

Data element for RTE:
* App data element + E2E header

End-2-End Protection: Description, End-2-End Profiles (p. 38)
* a set of standardized and configurable End-2-End profiles is specified
* CRC Checksum
* Sequence Counter
* Alive Counter
* A specific ID for every port data element sent over a port
* Timeout detection

Three End-2-End Profiles:
* Profile 1
* Profile 2
* Profile 4

Upcoming (AUTOSAR) releases:
* Profile 5
* Profile 6

PDUs up to 4kB in size supported (p. 43)

End-2-End Profiles 1 and 2:
* support an ASIL-D compliant transmission of up to 30 or 42 byte PDUs

End-2-End Profiles 4:
* designed for ASIL-D compliant transmission of long data
* 32-Bit CRC polynomial

End-2-End Protection: Description, End-2-End State Machine (p. 44)
