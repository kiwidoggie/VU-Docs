---
title: PlayerFilterEntityData (Frostbite Container)
---
### Base Classes

[EntityData](EntityData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                       | Description                                                                                                                         |
| --------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| PlayerFilterEntityData()                                                          | Create a new instance of this container type.                                                                                       |
| PlayerFilterEntityData(PlayerFilterEntityData other)                              | Create a reference copy of an instance of the same type.                                                                            |
| PlayerFilterEntityData([EntityData](EntityData) other)                            | Upcast an instance of type [EntityData](EntityData) to [PlayerFilterEntityData](PlayerFilterEntityData).                            |
| PlayerFilterEntityData([GameObjectData](GameObjectData) other)                    | Upcast an instance of type [GameObjectData](GameObjectData) to [PlayerFilterEntityData](PlayerFilterEntityData).                    |
| PlayerFilterEntityData([GameDataContainer](GameDataContainer) other)              | Upcast an instance of type [GameDataContainer](GameDataContainer) to [PlayerFilterEntityData](PlayerFilterEntityData).              |
| PlayerFilterEntityData([DataContainer](/vext/ref/cls/shr/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/cls/shr/datacontainer) to [PlayerFilterEntityData](PlayerFilterEntityData). |

## Properties

| Name                | Type           | Description |
| ------------------- | -------------- | ----------- |
| realm               | [Realm](Realm) |             |
| invertFilter        | bool           |             |
| forwardToSpectators | bool           |             |

## Methods

| Type                                             | Name            | Parameters                                     |
| ------------------------------------------------ | --------------- | ---------------------------------------------- |
| [PlayerFilterEntityData](PlayerFilterEntityData) | [Clone](#clone) | \[[Guid](/vext/ref/cls/shr/guid) **guid**\] |

### Clone

> [PlayerFilterEntityData](PlayerFilterEntityData) **Clone**(\[[Guid](/vext/ref/cls/shr/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |