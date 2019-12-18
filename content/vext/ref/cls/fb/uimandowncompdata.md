---
title: UIManDownCompData (Frostbite Container)
---
### Base Classes

[UIComponentData](UIComponentData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                  | Description                                                                                                               |
| ---------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------- |
| UIManDownCompData()                                                          | Create a new instance of this container type.                                                                             |
| UIManDownCompData(UIManDownCompData other)                                   | Create a reference copy of an instance of the same type.                                                                  |
| UIManDownCompData([UIComponentData](UIComponentData) other)                  | Upcast an instance of type [UIComponentData](UIComponentData) to [UIManDownCompData](UIManDownCompData).                  |
| UIManDownCompData([Asset](Asset) other)                                      | Upcast an instance of type [Asset](Asset) to [UIManDownCompData](UIManDownCompData).                                      |
| UIManDownCompData([DataContainer](/vext/ref/cls/shr/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/cls/shr/datacontainer) to [UIManDownCompData](UIManDownCompData). |

## Properties

| Name                 | Type   | Description |
| -------------------- | ------ | ----------- |
| delayManDownTextTime | number |             |

## Methods

| Type                                   | Name            | Parameters                                     |
| -------------------------------------- | --------------- | ---------------------------------------------- |
| [UIManDownCompData](UIManDownCompData) | [Clone](#clone) | \[[Guid](/vext/ref/cls/shr/guid) **guid**\] |

### Clone

> [UIManDownCompData](UIManDownCompData) **Clone**(\[[Guid](/vext/ref/cls/shr/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |