---
title: VignetteData (Client Class)
---
## Description

## Constructors

| Constructor                      | Description                                              |
| -------------------------------- | -------------------------------------------------------- |
| VignetteData()                   | Create a new instance of this container type.            |
| VignetteData(VignetteData other) | Create a reference copy of an instance of the same type. |

## Properties

| Name     | Type                               | Description |
| -------- | ---------------------------------- | ----------- |
| scale    | [Vec2](/vext/ref/cls/shr/Vec2)  |             |
| color    | [Vec3](/vext/ref/cls/shr/Vec3)  |             |
| realm    | [Realm](/vext/ref/cls/fb/realm) |             |
| exponent | number                             |             |
| opacity  | number                             |             |
| enable   | bool                               |             |

## Methods

| Type                                              | Name            | Parameters |
| ------------------------------------------------- | --------------- | ---------- |
| [VignetteData](/vext/ref/cls/clt/vignettedata) | [Clone](#clone) |            |

### Clone

> [VignetteData](/vext/ref/cls/clt/vignettedata) **Clone**()

Creates a shallow-copy clone of the instance.