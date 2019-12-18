---
title: UIEventAsset (Frostbite Container)
---
### Base Classes

[Asset](Asset)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                             | Description                                                                                                     |
| ----------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- |
| UIEventAsset()                                                          | Create a new instance of this container type.                                                                   |
| UIEventAsset(UIEventAsset other)                                        | Create a reference copy of an instance of the same type.                                                        |
| UIEventAsset([Asset](Asset) other)                                      | Upcast an instance of type [Asset](Asset) to [UIEventAsset](UIEventAsset).                                      |
| UIEventAsset([DataContainer](/vext/ref/cls/shr/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/cls/shr/datacontainer) to [UIEventAsset](UIEventAsset). |

## Properties

| Name      | Type       | Description |
| --------- | ---------- | ----------- |
| category  | string     |             |
| eventList | string\[\] |             |

## Methods

| Type                         | Name            | Parameters                                     |
| ---------------------------- | --------------- | ---------------------------------------------- |
| [UIEventAsset](UIEventAsset) | [Clone](#clone) | \[[Guid](/vext/ref/cls/shr/guid) **guid**\] |

### Clone

> [UIEventAsset](UIEventAsset) **Clone**(\[[Guid](/vext/ref/cls/shr/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |