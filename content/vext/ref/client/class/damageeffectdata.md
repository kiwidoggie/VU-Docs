---
title: DamageEffectData
---
## Description

## Constructors

| Constructor                              | Description                                              |
| ---------------------------------------- | -------------------------------------------------------- |
| DamageEffectData()                       | Create a new instance of this container type.            |
| DamageEffectData(DamageEffectData other) | Create a reference copy of an instance of the same type. |

## Properties

| Name                               | Type                                                                 | Description |
| ---------------------------------- | -------------------------------------------------------------------- | ----------- |
| rightDamage                        | [Vec4](/vext/ref/shared/class/Vec4)                                    |             |
| topDamage                          | [Vec4](/vext/ref/shared/class/Vec4)                                    |             |
| leftDamage                         | [Vec4](/vext/ref/shared/class/Vec4)                                    |             |
| bottomDamage                       | [Vec4](/vext/ref/shared/class/Vec4)                                    |             |
| outerFrameOpacity                  | number                                                               |             |
| innerFrameOpacity                  | number                                                               |             |
| frameWidth                         | number                                                               |             |
| shader                             | [SurfaceShaderBaseAsset](/vext/ref/fb/surfaceshaderbaseasset) |             |
| startCriticalEffectHealthThreshold | number                                                               |             |
| endCriticalEffectHealthThreshold   | number                                                               |             |
| minDamagePercentageThreshold       | number                                                               |             |
| fallofTime                         | number                                                               |             |
| maxOpacityDamagePercentage         | number                                                               |             |
| realm                              | [Realm](/vext/ref/fb/realm)                                   |             |
| debugDamage                        | bool                                                                 |             |

## Methods

| Type                                                      | Name            | Parameters |
| --------------------------------------------------------- | --------------- | ---------- |
| [DamageEffectData](/vext/ref/cls/clt/damageeffectdata) | [Clone](#clone) |            |

### Clone

> [DamageEffectData](/vext/ref/cls/clt/damageeffectdata) **Clone**()

Creates a shallow-copy clone of the instance.