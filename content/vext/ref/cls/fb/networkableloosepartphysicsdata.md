---
title: NetworkableLoosePartPhysicsData (Frostbite Container)
---
### Base Classes

[LoosePartPhysicsData](LoosePartPhysicsData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                                | Description                                                                                                                                           |
| ------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| NetworkableLoosePartPhysicsData()                                                          | Create a new instance of this container type.                                                                                                         |
| NetworkableLoosePartPhysicsData(NetworkableLoosePartPhysicsData other)                     | Create a reference copy of an instance of the same type.                                                                                              |
| NetworkableLoosePartPhysicsData([LoosePartPhysicsData](LoosePartPhysicsData) other)        | Upcast an instance of type [LoosePartPhysicsData](LoosePartPhysicsData) to [NetworkableLoosePartPhysicsData](NetworkableLoosePartPhysicsData).        |
| NetworkableLoosePartPhysicsData([DataContainer](/vext/ref/cls/shr/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/cls/shr/datacontainer) to [NetworkableLoosePartPhysicsData](NetworkableLoosePartPhysicsData). |

## Properties

| Name      | Type | Description |
| --------- | ---- | ----------- |
| networked | bool |             |

## Methods

| Type                                                               | Name            | Parameters                                     |
| ------------------------------------------------------------------ | --------------- | ---------------------------------------------- |
| [NetworkableLoosePartPhysicsData](NetworkableLoosePartPhysicsData) | [Clone](#clone) | \[[Guid](/vext/ref/cls/shr/guid) **guid**\] |

### Clone

> [NetworkableLoosePartPhysicsData](NetworkableLoosePartPhysicsData) **Clone**(\[[Guid](/vext/ref/cls/shr/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |