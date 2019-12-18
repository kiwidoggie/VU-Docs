---
title: UILeaderboardData (Frostbite Structure)
---
## Description

A structure type representing a Frostbite data type.

## Constructors

| Constructor                                | Description                                              |
| ------------------------------------------ | -------------------------------------------------------- |
| UILeaderboardData()                        | Create a new instance of this structure type.            |
| UILeaderboardData(UILeaderboardData other) | Create a reference copy of a structure of the same type. |

## Properties

| Name        | Type   | Description |
| ----------- | ------ | ----------- |
| name        | string |             |
| description | string |             |

## Methods

| Type                                   | Name            | Parameters |
| -------------------------------------- | --------------- | ---------- |
| [UILeaderboardData](UILeaderboardData) | [Clone](#clone) |            |

### Clone

> [UILeaderboardData](UILeaderboardData) **Clone**()

Creates a shallow-copy clone of the structure. Works similarly to [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone).