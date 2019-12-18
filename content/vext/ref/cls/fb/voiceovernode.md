---
title: VoiceOverNode (Frostbite Container)
---
### Base Classes

[DataContainer](/vext/ref/cls/shr/datacontainer)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                              | Description                                                                                                       |
| ------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------- |
| VoiceOverNode()                                                          | Create a new instance of this container type.                                                                     |
| VoiceOverNode(VoiceOverNode other)                                       | Create a reference copy of an instance of the same type.                                                          |
| VoiceOverNode([DataContainer](/vext/ref/cls/shr/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/cls/shr/datacontainer) to [VoiceOverNode](VoiceOverNode). |

## Methods

| Type                           | Name            | Parameters                                     |
| ------------------------------ | --------------- | ---------------------------------------------- |
| [VoiceOverNode](VoiceOverNode) | [Clone](#clone) | \[[Guid](/vext/ref/cls/shr/guid) **guid**\] |

### Clone

> [VoiceOverNode](VoiceOverNode) **Clone**(\[[Guid](/vext/ref/cls/shr/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |