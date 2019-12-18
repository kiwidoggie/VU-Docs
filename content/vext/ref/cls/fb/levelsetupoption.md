---
title: LevelSetupOption (Frostbite Structure)
---
## Description

A structure type representing a Frostbite data type.

## Constructors

| Constructor                              | Description                                              |
| ---------------------------------------- | -------------------------------------------------------- |
| LevelSetupOption()                       | Create a new instance of this structure type.            |
| LevelSetupOption(LevelSetupOption other) | Create a reference copy of a structure of the same type. |

## Properties

| Name      | Type   | Description |
| --------- | ------ | ----------- |
| criterion | string |             |
| value     | string |             |

## Methods

| Type                                 | Name            | Parameters |
| ------------------------------------ | --------------- | ---------- |
| [LevelSetupOption](LevelSetupOption) | [Clone](#clone) |            |

### Clone

> [LevelSetupOption](LevelSetupOption) **Clone**()

Creates a shallow-copy clone of the structure. Works similarly to [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone).