---
title: PhysicsPropertyRelationPropertyData (Frostbite Container)
---
### Base Classes

[MaterialRelationPropertyData](MaterialRelationPropertyData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                                             | Description                                                                                                                                                            |
| ------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| PhysicsPropertyRelationPropertyData()                                                                   | Create a new instance of this container type.                                                                                                                          |
| PhysicsPropertyRelationPropertyData(PhysicsPropertyRelationPropertyData other)                          | Create a reference copy of an instance of the same type.                                                                                                               |
| PhysicsPropertyRelationPropertyData([MaterialRelationPropertyData](MaterialRelationPropertyData) other) | Upcast an instance of type [MaterialRelationPropertyData](MaterialRelationPropertyData) to [PhysicsPropertyRelationPropertyData](PhysicsPropertyRelationPropertyData). |
| PhysicsPropertyRelationPropertyData([DataContainer](/vext/ref/cls/shr/datacontainer) other)          | Upcast an instance of type [DataContainer](/vext/ref/cls/shr/datacontainer) to [PhysicsPropertyRelationPropertyData](PhysicsPropertyRelationPropertyData).          |

## Methods

| Type                                                                       | Name            | Parameters                                     |
| -------------------------------------------------------------------------- | --------------- | ---------------------------------------------- |
| [PhysicsPropertyRelationPropertyData](PhysicsPropertyRelationPropertyData) | [Clone](#clone) | \[[Guid](/vext/ref/cls/shr/guid) **guid**\] |

### Clone

> [PhysicsPropertyRelationPropertyData](PhysicsPropertyRelationPropertyData) **Clone**(\[[Guid](/vext/ref/cls/shr/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |