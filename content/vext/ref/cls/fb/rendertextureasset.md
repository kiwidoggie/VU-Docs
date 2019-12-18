---
title: RenderTextureAsset (Frostbite Container)
---
### Base Classes

[TextureBaseAsset](TextureBaseAsset)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                   | Description                                                                                                                 |
| ----------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| RenderTextureAsset()                                                          | Create a new instance of this container type.                                                                               |
| RenderTextureAsset(RenderTextureAsset other)                                  | Create a reference copy of an instance of the same type.                                                                    |
| RenderTextureAsset([TextureBaseAsset](TextureBaseAsset) other)                | Upcast an instance of type [TextureBaseAsset](TextureBaseAsset) to [RenderTextureAsset](RenderTextureAsset).                |
| RenderTextureAsset([Asset](Asset) other)                                      | Upcast an instance of type [Asset](Asset) to [RenderTextureAsset](RenderTextureAsset).                                      |
| RenderTextureAsset([DataContainer](/vext/ref/cls/shr/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/cls/shr/datacontainer) to [RenderTextureAsset](RenderTextureAsset). |

## Methods

| Type                                     | Name            | Parameters                                     |
| ---------------------------------------- | --------------- | ---------------------------------------------- |
| [RenderTextureAsset](RenderTextureAsset) | [Clone](#clone) | \[[Guid](/vext/ref/cls/shr/guid) **guid**\] |

### Clone

> [RenderTextureAsset](RenderTextureAsset) **Clone**(\[[Guid](/vext/ref/cls/shr/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |