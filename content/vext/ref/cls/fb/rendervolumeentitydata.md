---
title: RenderVolumeEntityData (Frostbite Container)
---
### Base Classes

[SpatialEntityData](SpatialEntityData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                       | Description                                                                                                                         |
| --------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| RenderVolumeEntityData()                                                          | Create a new instance of this container type.                                                                                       |
| RenderVolumeEntityData(RenderVolumeEntityData other)                              | Create a reference copy of an instance of the same type.                                                                            |
| RenderVolumeEntityData([SpatialEntityData](SpatialEntityData) other)              | Upcast an instance of type [SpatialEntityData](SpatialEntityData) to [RenderVolumeEntityData](RenderVolumeEntityData).              |
| RenderVolumeEntityData([EntityData](EntityData) other)                            | Upcast an instance of type [EntityData](EntityData) to [RenderVolumeEntityData](RenderVolumeEntityData).                            |
| RenderVolumeEntityData([GameObjectData](GameObjectData) other)                    | Upcast an instance of type [GameObjectData](GameObjectData) to [RenderVolumeEntityData](RenderVolumeEntityData).                    |
| RenderVolumeEntityData([GameDataContainer](GameDataContainer) other)              | Upcast an instance of type [GameDataContainer](GameDataContainer) to [RenderVolumeEntityData](RenderVolumeEntityData).              |
| RenderVolumeEntityData([DataContainer](/vext/ref/cls/shr/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/cls/shr/datacontainer) to [RenderVolumeEntityData](RenderVolumeEntityData). |

## Properties

| Name          | Type                                                               | Description |
| ------------- | ------------------------------------------------------------------ | ----------- |
| userMasks     | [Vec4](/vext/ref/cls/shr/Vec4)                                  |             |
| shader        | [SurfaceShaderInstanceDataStruct](SurfaceShaderInstanceDataStruct) |             |
| transformType | [RenderVolumeTransformType](RenderVolumeTransformType)             |             |
| enabled       | bool                                                               |             |

## Methods

| Type                                             | Name            | Parameters                                     |
| ------------------------------------------------ | --------------- | ---------------------------------------------- |
| [RenderVolumeEntityData](RenderVolumeEntityData) | [Clone](#clone) | \[[Guid](/vext/ref/cls/shr/guid) **guid**\] |

### Clone

> [RenderVolumeEntityData](RenderVolumeEntityData) **Clone**(\[[Guid](/vext/ref/cls/shr/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |