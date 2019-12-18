---
title: ProfileOptionDataEnumItem (Frostbite Structure)
---
## Description

A structure type representing a Frostbite data type.

## Constructors

| Constructor                                                | Description                                              |
| ---------------------------------------------------------- | -------------------------------------------------------- |
| ProfileOptionDataEnumItem()                                | Create a new instance of this structure type.            |
| ProfileOptionDataEnumItem(ProfileOptionDataEnumItem other) | Create a reference copy of a structure of the same type. |

## Properties

| Name        | Type   | Description |
| ----------- | ------ | ----------- |
| displayName | string |             |
| default     | bool   |             |

## Methods

| Type                                                   | Name            | Parameters |
| ------------------------------------------------------ | --------------- | ---------- |
| [ProfileOptionDataEnumItem](ProfileOptionDataEnumItem) | [Clone](#clone) |            |

### Clone

> [ProfileOptionDataEnumItem](ProfileOptionDataEnumItem) **Clone**()

Creates a shallow-copy clone of the structure. Works similarly to [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone).