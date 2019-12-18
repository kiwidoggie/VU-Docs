---
title: TurnEffectData (Frostbite Structure)
---
## Description

A structure type representing a Frostbite data type.

## Constructors

| Constructor                          | Description                                              |
| ------------------------------------ | -------------------------------------------------------- |
| TurnEffectData()                     | Create a new instance of this structure type.            |
| TurnEffectData(TurnEffectData other) | Create a reference copy of a structure of the same type. |

## Properties

| Name                  | Type   | Description |
| --------------------- | ------ | ----------- |
| maxRollAngle          | number |             |
| maxPitchAngle         | number |             |
| yawVelocityThreshhold | number |             |
| velocityThreshhold    | number |             |
| safeTime              | number |             |
| beginTime             | number |             |
| holdTime              | number |             |
| endTime               | number |             |

## Methods

| Type                             | Name            | Parameters |
| -------------------------------- | --------------- | ---------- |
| [TurnEffectData](TurnEffectData) | [Clone](#clone) |            |

### Clone

> [TurnEffectData](TurnEffectData) **Clone**()

Creates a shallow-copy clone of the structure. Works similarly to [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone).