---
title: SpatialReferenceObjectData (Frostbite Container)
---
### Base Classes

[ReferenceObjectData](ReferenceObjectData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                           | Description                                                                                                                                 |
| ------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| SpatialReferenceObjectData()                                                          | Create a new instance of this container type.                                                                                               |
| SpatialReferenceObjectData(SpatialReferenceObjectData other)                          | Create a reference copy of an instance of the same type.                                                                                    |
| SpatialReferenceObjectData([ReferenceObjectData](ReferenceObjectData) other)          | Upcast an instance of type [ReferenceObjectData](ReferenceObjectData) to [SpatialReferenceObjectData](SpatialReferenceObjectData).          |
| SpatialReferenceObjectData([GameObjectData](GameObjectData) other)                    | Upcast an instance of type [GameObjectData](GameObjectData) to [SpatialReferenceObjectData](SpatialReferenceObjectData).                    |
| SpatialReferenceObjectData([GameDataContainer](GameDataContainer) other)              | Upcast an instance of type [GameDataContainer](GameDataContainer) to [SpatialReferenceObjectData](SpatialReferenceObjectData).              |
| SpatialReferenceObjectData([DataContainer](/vext/ref/cls/shr/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/cls/shr/datacontainer) to [SpatialReferenceObjectData](SpatialReferenceObjectData). |

## Methods

| Type                                                     | Name            | Parameters                                     |
| -------------------------------------------------------- | --------------- | ---------------------------------------------- |
| [SpatialReferenceObjectData](SpatialReferenceObjectData) | [Clone](#clone) | \[[Guid](/vext/ref/cls/shr/guid) **guid**\] |

### Clone

> [SpatialReferenceObjectData](SpatialReferenceObjectData) **Clone**(\[[Guid](/vext/ref/cls/shr/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |