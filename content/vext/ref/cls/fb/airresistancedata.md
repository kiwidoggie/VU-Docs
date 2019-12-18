---
title: AirResistanceData (Frostbite Container)
---
### Base Classes

[ProcessorData](ProcessorData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                  | Description                                                                                                               |
| ---------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------- |
| AirResistanceData()                                                          | Create a new instance of this container type.                                                                             |
| AirResistanceData(AirResistanceData other)                                   | Create a reference copy of an instance of the same type.                                                                  |
| AirResistanceData([ProcessorData](ProcessorData) other)                      | Upcast an instance of type [ProcessorData](ProcessorData) to [AirResistanceData](AirResistanceData).                      |
| AirResistanceData([EmitterComponentData](EmitterComponentData) other)        | Upcast an instance of type [EmitterComponentData](EmitterComponentData) to [AirResistanceData](AirResistanceData).        |
| AirResistanceData([DataContainer](/vext/ref/cls/shr/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/cls/shr/datacontainer) to [AirResistanceData](AirResistanceData). |

## Properties

| Name       | Type   | Description |
| ---------- | ------ | ----------- |
| dragFactor | number |             |

## Methods

| Type                                   | Name            | Parameters                                     |
| -------------------------------------- | --------------- | ---------------------------------------------- |
| [AirResistanceData](AirResistanceData) | [Clone](#clone) | \[[Guid](/vext/ref/cls/shr/guid) **guid**\] |

### Clone

> [AirResistanceData](AirResistanceData) **Clone**(\[[Guid](/vext/ref/cls/shr/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |