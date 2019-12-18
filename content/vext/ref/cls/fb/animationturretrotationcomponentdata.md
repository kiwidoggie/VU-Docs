---
title: AnimationTurretRotationComponentData (Frostbite Container)
---
### Base Classes

[ComponentData](ComponentData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                                     | Description                                                                                                                                                     |
| ----------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| AnimationTurretRotationComponentData()                                                          | Create a new instance of this container type.                                                                                                                   |
| AnimationTurretRotationComponentData(AnimationTurretRotationComponentData other)                | Create a reference copy of an instance of the same type.                                                                                                        |
| AnimationTurretRotationComponentData([ComponentData](ComponentData) other)                      | Upcast an instance of type [ComponentData](ComponentData) to [AnimationTurretRotationComponentData](AnimationTurretRotationComponentData).                      |
| AnimationTurretRotationComponentData([GameObjectData](GameObjectData) other)                    | Upcast an instance of type [GameObjectData](GameObjectData) to [AnimationTurretRotationComponentData](AnimationTurretRotationComponentData).                    |
| AnimationTurretRotationComponentData([GameDataContainer](GameDataContainer) other)              | Upcast an instance of type [GameDataContainer](GameDataContainer) to [AnimationTurretRotationComponentData](AnimationTurretRotationComponentData).              |
| AnimationTurretRotationComponentData([DataContainer](/vext/ref/cls/shr/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/cls/shr/datacontainer) to [AnimationTurretRotationComponentData](AnimationTurretRotationComponentData). |

## Properties

| Name                     | Type                                         | Description |
| ------------------------ | -------------------------------------------- | ----------- |
| rotations                | [TurretRotationInfo](TurretRotationInfo)\[\] |             |
| soldierBaseIndex         | number                                       |             |
| useVehicleWorldTransform | bool                                         |             |
| outputWorldTransform     | bool                                         |             |

## Methods

| Type                                                                         | Name            | Parameters                                     |
| ---------------------------------------------------------------------------- | --------------- | ---------------------------------------------- |
| [AnimationTurretRotationComponentData](AnimationTurretRotationComponentData) | [Clone](#clone) | \[[Guid](/vext/ref/cls/shr/guid) **guid**\] |

### Clone

> [AnimationTurretRotationComponentData](AnimationTurretRotationComponentData) **Clone**(\[[Guid](/vext/ref/cls/shr/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |