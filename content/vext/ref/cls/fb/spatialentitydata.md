---
title: SpatialEntityData (Frostbite Container)
---
### Base Classes

[EntityData](EntityData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                  | Description                                                                                                               |
| ---------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------- |
| SpatialEntityData()                                                          | Create a new instance of this container type.                                                                             |
| SpatialEntityData(SpatialEntityData other)                                   | Create a reference copy of an instance of the same type.                                                                  |
| SpatialEntityData([EntityData](EntityData) other)                            | Upcast an instance of type [EntityData](EntityData) to [SpatialEntityData](SpatialEntityData).                            |
| SpatialEntityData([GameObjectData](GameObjectData) other)                    | Upcast an instance of type [GameObjectData](GameObjectData) to [SpatialEntityData](SpatialEntityData).                    |
| SpatialEntityData([GameDataContainer](GameDataContainer) other)              | Upcast an instance of type [GameDataContainer](GameDataContainer) to [SpatialEntityData](SpatialEntityData).              |
| SpatialEntityData([DataContainer](/vext/ref/cls/shr/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/cls/shr/datacontainer) to [SpatialEntityData](SpatialEntityData). |

## Properties

| Name      | Type                                                    | Description |
| --------- | ------------------------------------------------------- | ----------- |
| transform | [LinearTransform](/vext/ref/cls/shr/LinearTransform) |             |

## Methods

| Type                                   | Name            | Parameters                                     |
| -------------------------------------- | --------------- | ---------------------------------------------- |
| [SpatialEntityData](SpatialEntityData) | [Clone](#clone) | \[[Guid](/vext/ref/cls/shr/guid) **guid**\] |

### Clone

> [SpatialEntityData](SpatialEntityData) **Clone**(\[[Guid](/vext/ref/cls/shr/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |