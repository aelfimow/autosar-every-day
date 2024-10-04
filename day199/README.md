# Day 199

* From AUTOSAR\_EXP\_NVDataHandling.pdf

Other features: `CRC` based comparison (p. 13)
* `CRC` generation routines: 8/16/32 bit
* parameter `NvMBlockUseCRCCompMechanism`
* only for blocks where this risk can be tolerated

Other features: Error recovery (p. 13)
* parameter `NvMRomBlockDataAddress`
* parameter `NvMInitBlockCallback`

Other features: Write Verification (p. 14)
* error `NVM_E_VERIFY_FAILED` is reported to `DEM`

Other features: `RAM` Block handling using the `NvM_SetRamBlockStatus` `API` (p. 14)
* During startup phase (`NvM_ReadAll`)
* During shutdown phase (`NvM_WriteAll`)

Other features: Resistant to changed software (p. 15)
