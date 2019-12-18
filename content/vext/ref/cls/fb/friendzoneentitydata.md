---
title: FriendZoneEntityData (Frostbite Container)
---
### Base Classes

[EntityData](EntityData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                     | Description                                                                                                                     |
| ------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------- |
| FriendZoneEntityData()                                                          | Create a new instance of this container type.                                                                                   |
| FriendZoneEntityData(FriendZoneEntityData other)                                | Create a reference copy of an instance of the same type.                                                                        |
| FriendZoneEntityData([EntityData](EntityData) other)                            | Upcast an instance of type [EntityData](EntityData) to [FriendZoneEntityData](FriendZoneEntityData).                            |
| FriendZoneEntityData([GameObjectData](GameObjectData) other)                    | Upcast an instance of type [GameObjectData](GameObjectData) to [FriendZoneEntityData](FriendZoneEntityData).                    |
| FriendZoneEntityData([GameDataContainer](GameDataContainer) other)              | Upcast an instance of type [GameDataContainer](GameDataContainer) to [FriendZoneEntityData](FriendZoneEntityData).              |
| FriendZoneEntityData([DataContainer](/vext/ref/cls/shr/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/cls/shr/datacontainer) to [FriendZoneEntityData](FriendZoneEntityData). |

## Properties

| Name                    | Type   | Description |
| ----------------------- | ------ | ----------- |
| enemyWeight             | number |             |
| friendlyWeight          | number |             |
| corpsTimeout            | number |             |
| corpsWeight             | number |             |
| countCorpsesForAllTeams | bool   |             |
| initialZoneRandomized   | bool   |             |

## Methods

| Type                                         | Name            | Parameters                                     |
| -------------------------------------------- | --------------- | ---------------------------------------------- |
| [FriendZoneEntityData](FriendZoneEntityData) | [Clone](#clone) | \[[Guid](/vext/ref/cls/shr/guid) **guid**\] |

### Clone

> [FriendZoneEntityData](FriendZoneEntityData) **Clone**(\[[Guid](/vext/ref/cls/shr/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |