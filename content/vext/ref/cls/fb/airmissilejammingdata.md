---
title: AirMissileJammingData (Frostbite Structure)
---
## Description

A structure type representing a Frostbite data type.

## Constructors

| Constructor                                        | Description                                              |
| -------------------------------------------------- | -------------------------------------------------------- |
| AirMissileJammingData()                            | Create a new instance of this structure type.            |
| AirMissileJammingData(AirMissileJammingData other) | Create a reference copy of a structure of the same type. |

## Properties

| Name                      | Type   | Description |
| ------------------------- | ------ | ----------- |
| minTurnSpeed              | number |             |
| maxRadius                 | number |             |
| minRadius                 | number |             |
| theta                     | number |             |
| phi                       | number |             |
| updateJammingPositionTime | number |             |
| maxTurnSpeed              | number |             |
| quietModeProbability      | number |             |
| quietModeTime             | number |             |
| jammingTime               | number |             |
| turnCalculationTime       | number |             |
| enableAirMissileJamming   | bool   |             |

## Methods

| Type                                           | Name            | Parameters |
| ---------------------------------------------- | --------------- | ---------- |
| [AirMissileJammingData](AirMissileJammingData) | [Clone](#clone) |            |

### Clone

> [AirMissileJammingData](AirMissileJammingData) **Clone**()

Creates a shallow-copy clone of the structure. Works similarly to [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone).