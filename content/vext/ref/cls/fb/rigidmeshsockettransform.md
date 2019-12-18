---
title: RigidMeshSocketTransform (Frostbite Structure)
---
## Description

A structure type representing a Frostbite data type.

## Constructors

| Constructor                                              | Description                                              |
| -------------------------------------------------------- | -------------------------------------------------------- |
| RigidMeshSocketTransform()                               | Create a new instance of this structure type.            |
| RigidMeshSocketTransform(RigidMeshSocketTransform other) | Create a reference copy of a structure of the same type. |

## Properties

| Name         | Type                                                           | Description |
| ------------ | -------------------------------------------------------------- | ----------- |
| transform    | [LinearTransform](/vext/ref/cls/shr/LinearTransform)        |             |
| socketObject | [WeaponRegularSocketObjectData](WeaponRegularSocketObjectData) |             |

## Methods

| Type                                                 | Name            | Parameters |
| ---------------------------------------------------- | --------------- | ---------- |
| [RigidMeshSocketTransform](RigidMeshSocketTransform) | [Clone](#clone) |            |

### Clone

> [RigidMeshSocketTransform](RigidMeshSocketTransform) **Clone**()

Creates a shallow-copy clone of the structure. Works similarly to [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone).