# Day 12

* From AUTOSAR\_EXP\_ApplicationLevelErrorHandling.pdf

Substitute values (p. 20)
* `initValue`
* `handleInvalid` attribute

Voting (p. 22)
* Example algorithms: simple majority, 2 out-of 3
* to be implemented at application level

Agreement (p. 23)
* no true agreement service exists (in AUTOSAR)

Checksums/Codes (p. 24)

Threats to data security (p. 25):
* spoofing: pretending to be someone else
* repudiation: denying a performed action
* denial of service
* elevation of privileges

Execution sequence monitoring (p. 26)

Aliveness monitoring (p. 28)

Three states (p. 29)
* `WDGM_MONITORING_OK`
* `WDGM_MONITORING_FAILED`
* `WDGM_MONITORING_EXPIRED`

Status and Mode Management (p. 29)

Signal meta information (p. 30):
* signal quality
* signal timestamp
* signal sequence number
* update information

Return value `Rte_IStatus` (p. 31)
* `RTE_E_OK`
* `RTE_E_INVALID`
* `RTE_E_MAX_AGE_EXCEEDED`
