---
title: EdgePointerData (Frostbite Structure)
---
## Description

A structure type representing a Frostbite data type.

## Constructors

| Constructor                            | Description                                              |
| -------------------------------------- | -------------------------------------------------------- |
| EdgePointerData()                      | Create a new instance of this structure type.            |
| EdgePointerData(EdgePointerData other) | Create a reference copy of a structure of the same type. |

## Properties

| Name           | Type   | Description |
| -------------- | ------ | ----------- |
| negativeXLimit | number |             |
| positiveXLimit | number |             |
| negativeYLimit | number |             |
| positiveYLimit | number |             |

## Methods

| Type                               | Name            | Parameters |
| ---------------------------------- | --------------- | ---------- |
| [EdgePointerData](EdgePointerData) | [Clone](#clone) |            |

### Clone

> [EdgePointerData](EdgePointerData) **Clone**()

Creates a shallow-copy clone of the structure. Works similarly to [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone).