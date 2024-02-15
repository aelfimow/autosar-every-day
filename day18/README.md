# Day 18

* From AUTOSAR\_EXP\_AIUserGuide.pdf

Metamodel representation of AI Table (p. 14)
* `M2` level

Category of Model Elements: STANDARD (p. 14)
* `PhysicalDimensions`
* `Units`
* `LifeCycleInfoSets`

Category of Model Elements: BLUEPRINT (p. 14)
* `ApplicationDataTypes`
* `CompuMethods`
* `DataConstraints`
* `KeywordSets`
* `PortInterfaces`
* `PortPrototypeBlueprints`
* `Collections`

Category of Model Elements: EXAMPLE (p. 15)
* `SwComponentTypes`
* `ApplicationDataTypes`
* `BlueprintMappingSets`
* `CompuMethods`
* `DataConstrs`
* `PortInterfaces`

`CompositionSwComponentType`
* allow the encapsulation of specific functionality by aggregating existing software-components (p. 16)
* is also a `SwComponentType`

```
M2::AUTOSARTemplates::SWComponentTemplate::Composition
```

`SwComponentType`
* multiple instantiation (p. 17)

(p. 19):
```
M2::AUTOSARTemplates::SWComponentTemplate:: Components
```
