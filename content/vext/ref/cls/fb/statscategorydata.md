---
title: StatsCategoryData (Frostbite Container)
---
### Base Classes

[StatsCategoryBaseData](StatsCategoryBaseData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                  | Description                                                                                                               |
| ---------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------- |
| StatsCategoryData()                                                          | Create a new instance of this container type.                                                                             |
| StatsCategoryData(StatsCategoryData other)                                   | Create a reference copy of an instance of the same type.                                                                  |
| StatsCategoryData([StatsCategoryBaseData](StatsCategoryBaseData) other)      | Upcast an instance of type [StatsCategoryBaseData](StatsCategoryBaseData) to [StatsCategoryData](StatsCategoryData).      |
| StatsCategoryData([TreeNodeBase](TreeNodeBase) other)                        | Upcast an instance of type [TreeNodeBase](TreeNodeBase) to [StatsCategoryData](StatsCategoryData).                        |
| StatsCategoryData([DataContainer](/vext/ref/cls/shr/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/cls/shr/datacontainer) to [StatsCategoryData](StatsCategoryData). |

## Properties

| Name       | Type                                       | Description |
| ---------- | ------------------------------------------ | ----------- |
| categories | [StatsCategoryData](StatsCategoryData)\[\] |             |
| members    | string\[\]                                 |             |

## Methods

| Type                                   | Name            | Parameters                                     |
| -------------------------------------- | --------------- | ---------------------------------------------- |
| [StatsCategoryData](StatsCategoryData) | [Clone](#clone) | \[[Guid](/vext/ref/cls/shr/guid) **guid**\] |

### Clone

> [StatsCategoryData](StatsCategoryData) **Clone**(\[[Guid](/vext/ref/cls/shr/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |