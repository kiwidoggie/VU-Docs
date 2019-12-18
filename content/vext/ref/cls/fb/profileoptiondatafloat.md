---
title: ProfileOptionDataFloat (Frostbite Container)
---
### Base Classes

[ProfileOptionData](ProfileOptionData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                       | Description                                                                                                                         |
| --------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| ProfileOptionDataFloat()                                                          | Create a new instance of this container type.                                                                                       |
| ProfileOptionDataFloat(ProfileOptionDataFloat other)                              | Create a reference copy of an instance of the same type.                                                                            |
| ProfileOptionDataFloat([ProfileOptionData](ProfileOptionData) other)              | Upcast an instance of type [ProfileOptionData](ProfileOptionData) to [ProfileOptionDataFloat](ProfileOptionDataFloat).              |
| ProfileOptionDataFloat([Asset](Asset) other)                                      | Upcast an instance of type [Asset](Asset) to [ProfileOptionDataFloat](ProfileOptionDataFloat).                                      |
| ProfileOptionDataFloat([DataContainer](/vext/ref/cls/shr/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/cls/shr/datacontainer) to [ProfileOptionDataFloat](ProfileOptionDataFloat). |

## Properties

| Name  | Type   | Description |
| ----- | ------ | ----------- |
| min   | number |             |
| max   | number |             |
| value | number |             |
| step  | number |             |

## Methods

| Type                                             | Name            | Parameters                                     |
| ------------------------------------------------ | --------------- | ---------------------------------------------- |
| [ProfileOptionDataFloat](ProfileOptionDataFloat) | [Clone](#clone) | \[[Guid](/vext/ref/cls/shr/guid) **guid**\] |

### Clone

> [ProfileOptionDataFloat](ProfileOptionDataFloat) **Clone**(\[[Guid](/vext/ref/cls/shr/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |