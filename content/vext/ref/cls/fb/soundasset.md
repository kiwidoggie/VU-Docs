---
title: SoundAsset (Frostbite Container)
---
### Base Classes

[Asset](Asset)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                           | Description                                                                                                 |
| --------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------- |
| SoundAsset()                                                          | Create a new instance of this container type.                                                               |
| SoundAsset(SoundAsset other)                                          | Create a reference copy of an instance of the same type.                                                    |
| SoundAsset([Asset](Asset) other)                                      | Upcast an instance of type [Asset](Asset) to [SoundAsset](SoundAsset).                                      |
| SoundAsset([DataContainer](/vext/ref/cls/shr/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/cls/shr/datacontainer) to [SoundAsset](SoundAsset). |

## Properties

| Name  | Type                             | Description |
| ----- | -------------------------------- | ----------- |
| scope | [SoundScopeData](SoundScopeData) |             |

## Methods

| Type                     | Name            | Parameters                                     |
| ------------------------ | --------------- | ---------------------------------------------- |
| [SoundAsset](SoundAsset) | [Clone](#clone) | \[[Guid](/vext/ref/cls/shr/guid) **guid**\] |

### Clone

> [SoundAsset](SoundAsset) **Clone**(\[[Guid](/vext/ref/cls/shr/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |