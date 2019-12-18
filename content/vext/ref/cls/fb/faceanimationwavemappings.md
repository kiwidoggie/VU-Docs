---
title: FaceAnimationWaveMappings (Frostbite Container)
---
### Base Classes

[DataContainer](/vext/ref/cls/shr/datacontainer)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                          | Description                                                                                                                               |
| ------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------- |
| FaceAnimationWaveMappings()                                                          | Create a new instance of this container type.                                                                                             |
| FaceAnimationWaveMappings(FaceAnimationWaveMappings other)                           | Create a reference copy of an instance of the same type.                                                                                  |
| FaceAnimationWaveMappings([DataContainer](/vext/ref/cls/shr/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/cls/shr/datacontainer) to [FaceAnimationWaveMappings](FaceAnimationWaveMappings). |

## Properties

| Name             | Type                                                     | Description |
| ---------------- | -------------------------------------------------------- | ----------- |
| antAsset         | [AntRef](AntRef)                                         |             |
| onStartedTalking | [AntRef](AntRef)                                         |             |
| mappings         | [FaceAnimationWaveMapping](FaceAnimationWaveMapping)\[\] |             |

## Methods

| Type                                                   | Name            | Parameters                                     |
| ------------------------------------------------------ | --------------- | ---------------------------------------------- |
| [FaceAnimationWaveMappings](FaceAnimationWaveMappings) | [Clone](#clone) | \[[Guid](/vext/ref/cls/shr/guid) **guid**\] |

### Clone

> [FaceAnimationWaveMappings](FaceAnimationWaveMappings) **Clone**(\[[Guid](/vext/ref/cls/shr/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |