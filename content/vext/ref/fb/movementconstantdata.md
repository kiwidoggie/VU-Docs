---
title: MovementConstantData
---
### Base Classes

[Asset](Asset)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                     | Description                                                                                                                     |
| ------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------- |
| MovementConstantData()                                                          | Create a new instance of this container type.                                                                                   |
| MovementConstantData(MovementConstantData other)                                | Create a reference copy of an instance of the same type.                                                                        |
| MovementConstantData([Asset](Asset) other)                                      | Upcast an instance of type [Asset](Asset) to [MovementConstantData](MovementConstantData).                                      |
| MovementConstantData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [MovementConstantData](MovementConstantData). |

## Properties

| Name                  | Type   | Description |
| --------------------- | ------ | ----------- |
| maxCrouchWalkDistance | number |             |

## Methods

| Type                                         | Name            | Parameters                                     |
| -------------------------------------------- | --------------- | ---------------------------------------------- |
| [MovementConstantData](MovementConstantData) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [MovementConstantData](MovementConstantData) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |