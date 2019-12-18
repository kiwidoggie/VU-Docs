---
title: JumpStateData (Frostbite Container)
---
### Base Classes

[CharacterStateData](CharacterStateData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                              | Description                                                                                                       |
| ------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------- |
| JumpStateData()                                                          | Create a new instance of this container type.                                                                     |
| JumpStateData(JumpStateData other)                                       | Create a reference copy of an instance of the same type.                                                          |
| JumpStateData([CharacterStateData](CharacterStateData) other)            | Upcast an instance of type [CharacterStateData](CharacterStateData) to [JumpStateData](JumpStateData).            |
| JumpStateData([DataContainer](/vext/ref/cls/shr/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/cls/shr/datacontainer) to [JumpStateData](JumpStateData). |

## Properties

| Name           | Type   | Description |
| -------------- | ------ | ----------- |
| jumpHeight     | number |             |
| jumpEffectSize | number |             |

## Methods

| Type                           | Name            | Parameters                                     |
| ------------------------------ | --------------- | ---------------------------------------------- |
| [JumpStateData](JumpStateData) | [Clone](#clone) | \[[Guid](/vext/ref/cls/shr/guid) **guid**\] |

### Clone

> [JumpStateData](JumpStateData) **Clone**(\[[Guid](/vext/ref/cls/shr/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |