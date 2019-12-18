---
title: CameraLoosePartPhysicsData (Frostbite Container)
---
### Base Classes

[LoosePartPhysicsData](LoosePartPhysicsData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                           | Description                                                                                                                                 |
| ------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| CameraLoosePartPhysicsData()                                                          | Create a new instance of this container type.                                                                                               |
| CameraLoosePartPhysicsData(CameraLoosePartPhysicsData other)                          | Create a reference copy of an instance of the same type.                                                                                    |
| CameraLoosePartPhysicsData([LoosePartPhysicsData](LoosePartPhysicsData) other)        | Upcast an instance of type [LoosePartPhysicsData](LoosePartPhysicsData) to [CameraLoosePartPhysicsData](CameraLoosePartPhysicsData).        |
| CameraLoosePartPhysicsData([DataContainer](/vext/ref/cls/shr/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/cls/shr/datacontainer) to [CameraLoosePartPhysicsData](CameraLoosePartPhysicsData). |

## Properties

| Name  | Type   | Description |
| ----- | ------ | ----------- |
| scale | number |             |

## Methods

| Type                                                     | Name            | Parameters                                     |
| -------------------------------------------------------- | --------------- | ---------------------------------------------- |
| [CameraLoosePartPhysicsData](CameraLoosePartPhysicsData) | [Clone](#clone) | \[[Guid](/vext/ref/cls/shr/guid) **guid**\] |

### Clone

> [CameraLoosePartPhysicsData](CameraLoosePartPhysicsData) **Clone**(\[[Guid](/vext/ref/cls/shr/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |