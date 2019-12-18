---
title: UIAsset (Frostbite Container)
---
### Base Classes

[Asset](Asset)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                        | Description                                                                                           |
| ------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------- |
| UIAsset()                                                          | Create a new instance of this container type.                                                         |
| UIAsset(UIAsset other)                                             | Create a reference copy of an instance of the same type.                                              |
| UIAsset([Asset](Asset) other)                                      | Upcast an instance of type [Asset](Asset) to [UIAsset](UIAsset).                                      |
| UIAsset([DataContainer](/vext/ref/cls/shr/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/cls/shr/datacontainer) to [UIAsset](UIAsset). |

## Methods

| Type               | Name            | Parameters                                     |
| ------------------ | --------------- | ---------------------------------------------- |
| [UIAsset](UIAsset) | [Clone](#clone) | \[[Guid](/vext/ref/cls/shr/guid) **guid**\] |

### Clone

> [UIAsset](UIAsset) **Clone**(\[[Guid](/vext/ref/cls/shr/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |