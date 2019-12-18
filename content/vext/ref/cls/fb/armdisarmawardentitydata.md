---
title: ArmDisarmAwardEntityData (Frostbite Container)
---
### Base Classes

[GameEntityData](GameEntityData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                         | Description                                                                                                                             |
| ----------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| ArmDisarmAwardEntityData()                                                          | Create a new instance of this container type.                                                                                           |
| ArmDisarmAwardEntityData(ArmDisarmAwardEntityData other)                            | Create a reference copy of an instance of the same type.                                                                                |
| ArmDisarmAwardEntityData([GameEntityData](GameEntityData) other)                    | Upcast an instance of type [GameEntityData](GameEntityData) to [ArmDisarmAwardEntityData](ArmDisarmAwardEntityData).                    |
| ArmDisarmAwardEntityData([SpatialEntityData](SpatialEntityData) other)              | Upcast an instance of type [SpatialEntityData](SpatialEntityData) to [ArmDisarmAwardEntityData](ArmDisarmAwardEntityData).              |
| ArmDisarmAwardEntityData([EntityData](EntityData) other)                            | Upcast an instance of type [EntityData](EntityData) to [ArmDisarmAwardEntityData](ArmDisarmAwardEntityData).                            |
| ArmDisarmAwardEntityData([GameObjectData](GameObjectData) other)                    | Upcast an instance of type [GameObjectData](GameObjectData) to [ArmDisarmAwardEntityData](ArmDisarmAwardEntityData).                    |
| ArmDisarmAwardEntityData([GameDataContainer](GameDataContainer) other)              | Upcast an instance of type [GameDataContainer](GameDataContainer) to [ArmDisarmAwardEntityData](ArmDisarmAwardEntityData).              |
| ArmDisarmAwardEntityData([DataContainer](/vext/ref/cls/shr/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/cls/shr/datacontainer) to [ArmDisarmAwardEntityData](ArmDisarmAwardEntityData). |

## Methods

| Type                                                 | Name            | Parameters                                     |
| ---------------------------------------------------- | --------------- | ---------------------------------------------- |
| [ArmDisarmAwardEntityData](ArmDisarmAwardEntityData) | [Clone](#clone) | \[[Guid](/vext/ref/cls/shr/guid) **guid**\] |

### Clone

> [ArmDisarmAwardEntityData](ArmDisarmAwardEntityData) **Clone**(\[[Guid](/vext/ref/cls/shr/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |