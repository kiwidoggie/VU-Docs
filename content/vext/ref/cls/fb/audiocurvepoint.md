---
title: AudioCurvePoint (Frostbite Structure)
---
## Description

A structure type representing a Frostbite data type.

## Constructors

| Constructor                            | Description                                              |
| -------------------------------------- | -------------------------------------------------------- |
| AudioCurvePoint()                      | Create a new instance of this structure type.            |
| AudioCurvePoint(AudioCurvePoint other) | Create a reference copy of a structure of the same type. |

## Properties

| Name | Type   | Description |
| ---- | ------ | ----------- |
| x    | number |             |
| y    | number |             |
| k    | number |             |

## Methods

| Type                               | Name            | Parameters |
| ---------------------------------- | --------------- | ---------- |
| [AudioCurvePoint](AudioCurvePoint) | [Clone](#clone) |            |

### Clone

> [AudioCurvePoint](AudioCurvePoint) **Clone**()

Creates a shallow-copy clone of the structure. Works similarly to [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone).