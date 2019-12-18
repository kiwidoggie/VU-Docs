---
title: AssetAabbs (Frostbite Structure)
---
## Description

A structure type representing a Frostbite data type.

## Constructors

| Constructor                  | Description                                              |
| ---------------------------- | -------------------------------------------------------- |
| AssetAabbs()                 | Create a new instance of this structure type.            |
| AssetAabbs(AssetAabbs other) | Create a reference copy of a structure of the same type. |

## Properties

| Name     | Type                                                      | Description |
| -------- | --------------------------------------------------------- | ----------- |
| partAabb | [AxisAlignedBox](/vext/ref/cls/shr/AxisAlignedBox)\[\] |             |

## Methods

| Type                     | Name            | Parameters |
| ------------------------ | --------------- | ---------- |
| [AssetAabbs](AssetAabbs) | [Clone](#clone) |            |

### Clone

> [AssetAabbs](AssetAabbs) **Clone**()

Creates a shallow-copy clone of the structure. Works similarly to [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone).