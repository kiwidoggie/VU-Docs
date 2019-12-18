---
title: CharacterLightingData (Client Class)
---
## Description

## Constructors

| Constructor                                        | Description                                              |
| -------------------------------------------------- | -------------------------------------------------------- |
| CharacterLightingData()                            | Create a new instance of this container type.            |
| CharacterLightingData(CharacterLightingData other) | Create a reference copy of an instance of the same type. |

## Properties

| Name                  | Type                                                               | Description |
| --------------------- | ------------------------------------------------------------------ | ----------- |
| bottomLight           | [Vec3](/vext/ref/cls/shr/Vec3)                                  |             |
| topLight              | [Vec3](/vext/ref/cls/shr/Vec3)                                  |             |
| characterLightingMode | [CharacterLightingMode](/vext/ref/cls/fb/characterlightingmode) |             |
| cameraUpRotation      | number                                                             |             |
| topLightDirY          | number                                                             |             |
| blendFactor           | number                                                             |             |
| topLightDirX          | number                                                             |             |
| lockToCameraDirection | bool                                                               |             |
| firstPersonEnable     | bool                                                               |             |
| characterLightEnable  | bool                                                               |             |

## Methods

| Type                                                                | Name            | Parameters |
| ------------------------------------------------------------------- | --------------- | ---------- |
| [CharacterLightingData](/vext/ref/cls/clt/characterlightingdata) | [Clone](#clone) |            |

### Clone

> [CharacterLightingData](/vext/ref/cls/clt/characterlightingdata) **Clone**()

Creates a shallow-copy clone of the instance.