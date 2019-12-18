---
title: MaterialRelationPenetrationData (Frostbite Container)
---
### Base Classes

[PhysicsPropertyRelationPropertyData](PhysicsPropertyRelationPropertyData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                                                       | Description                                                                                                                                                                  |
| ----------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| MaterialRelationPenetrationData()                                                                                 | Create a new instance of this container type.                                                                                                                                |
| MaterialRelationPenetrationData(MaterialRelationPenetrationData other)                                            | Create a reference copy of an instance of the same type.                                                                                                                     |
| MaterialRelationPenetrationData([PhysicsPropertyRelationPropertyData](PhysicsPropertyRelationPropertyData) other) | Upcast an instance of type [PhysicsPropertyRelationPropertyData](PhysicsPropertyRelationPropertyData) to [MaterialRelationPenetrationData](MaterialRelationPenetrationData). |
| MaterialRelationPenetrationData([MaterialRelationPropertyData](MaterialRelationPropertyData) other)               | Upcast an instance of type [MaterialRelationPropertyData](MaterialRelationPropertyData) to [MaterialRelationPenetrationData](MaterialRelationPenetrationData).               |
| MaterialRelationPenetrationData([DataContainer](/vext/ref/cls/shr/datacontainer) other)                        | Upcast an instance of type [DataContainer](/vext/ref/cls/shr/datacontainer) to [MaterialRelationPenetrationData](MaterialRelationPenetrationData).                        |

## Properties

| Name           | Type | Description |
| -------------- | ---- | ----------- |
| neverPenetrate | bool |             |

## Methods

| Type                                                               | Name            | Parameters                                     |
| ------------------------------------------------------------------ | --------------- | ---------------------------------------------- |
| [MaterialRelationPenetrationData](MaterialRelationPenetrationData) | [Clone](#clone) | \[[Guid](/vext/ref/cls/shr/guid) **guid**\] |

### Clone

> [MaterialRelationPenetrationData](MaterialRelationPenetrationData) **Clone**(\[[Guid](/vext/ref/cls/shr/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |