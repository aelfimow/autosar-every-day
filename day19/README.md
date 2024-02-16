# Day 19

* From AUTOSAR\_EXP\_AIUserGuide.pdf

`PortPrototypes` (p. 21)
* either required or provided type

`RPortPrototype`: require-port

`PPortPrototype`: provider-port

Rules and Recommendations for the usage of Float data (p. 23)
* use 1:1 Scaling
* f64 is not recommended

(p. 24)
```
M2::AUTOSARTemplates::SWComponentTemplate::PortInterface
```

`SenderReceiverInterfaces` (p. 25)
* one or more receivers

`ClientServer` Communication (p. 26)
* synchronous operation call
* asynchronous operation call

`DataTypes` (p. 27)
* `ApplicationDataType`
```
M2::AUTOSARTemplates::SWComponentTemplate::DataType::DataTypes
```
* `ApplicationArrayDataType` with `maxNumberOfElements`
* `ApplicationRecordDataType`

Physical Units (p. 33)

Keyword attributes: (p. 35)
* ShortName
* longName
* desc
* abbrName
* classification
