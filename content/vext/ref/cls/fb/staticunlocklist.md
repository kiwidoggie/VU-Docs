---
title: StaticUnlockList (Frostbite Container)
---
### Base Classes

[Asset](Asset)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                 | Description                                                                                                             |
| --------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- |
| StaticUnlockList()                                                          | Create a new instance of this container type.                                                                           |
| StaticUnlockList(StaticUnlockList other)                                    | Create a reference copy of an instance of the same type.                                                                |
| StaticUnlockList([Asset](Asset) other)                                      | Upcast an instance of type [Asset](Asset) to [StaticUnlockList](StaticUnlockList).                                      |
| StaticUnlockList([DataContainer](/vext/ref/cls/shr/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/cls/shr/datacontainer) to [StaticUnlockList](StaticUnlockList). |

## Properties

| Name        | Type                                   | Description |
| ----------- | -------------------------------------- | ----------- |
| unlockInfos | [BasicUnlockInfo](BasicUnlockInfo)\[\] |             |

## Methods

| Type                                 | Name            | Parameters                                     |
| ------------------------------------ | --------------- | ---------------------------------------------- |
| [StaticUnlockList](StaticUnlockList) | [Clone](#clone) | \[[Guid](/vext/ref/cls/shr/guid) **guid**\] |

### Clone

> [StaticUnlockList](StaticUnlockList) **Clone**(\[[Guid](/vext/ref/cls/shr/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |