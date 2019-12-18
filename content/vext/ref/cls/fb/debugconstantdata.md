---
title: DebugConstantData (Frostbite Container)
---
### Base Classes

[Asset](Asset)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                  | Description                                                                                                               |
| ---------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------- |
| DebugConstantData()                                                          | Create a new instance of this container type.                                                                             |
| DebugConstantData(DebugConstantData other)                                   | Create a reference copy of an instance of the same type.                                                                  |
| DebugConstantData([Asset](Asset) other)                                      | Upcast an instance of type [Asset](Asset) to [DebugConstantData](DebugConstantData).                                      |
| DebugConstantData([DataContainer](/vext/ref/cls/shr/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/cls/shr/datacontainer) to [DebugConstantData](DebugConstantData). |

## Properties

| Name              | Type   | Description |
| ----------------- | ------ | ----------- |
| botDebugDistance  | number |             |
| inViewModeFOV     | number |             |
| graphDataBuffer   | number |             |
| minDecisionTime   | number |             |
| inaccuracyEnabled | bool   |             |

## Methods

| Type                                   | Name            | Parameters                                     |
| -------------------------------------- | --------------- | ---------------------------------------------- |
| [DebugConstantData](DebugConstantData) | [Clone](#clone) | \[[Guid](/vext/ref/cls/shr/guid) **guid**\] |

### Clone

> [DebugConstantData](DebugConstantData) **Clone**(\[[Guid](/vext/ref/cls/shr/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |