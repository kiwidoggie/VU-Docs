---
title: MultiCrossfaderGroup (Frostbite Container)
---
### Base Classes

[AudioGraphNodePortGroup](AudioGraphNodePortGroup)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                     | Description                                                                                                                     |
| ------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------- |
| MultiCrossfaderGroup()                                                          | Create a new instance of this container type.                                                                                   |
| MultiCrossfaderGroup(MultiCrossfaderGroup other)                                | Create a reference copy of an instance of the same type.                                                                        |
| MultiCrossfaderGroup([AudioGraphNodePortGroup](AudioGraphNodePortGroup) other)  | Upcast an instance of type [AudioGraphNodePortGroup](AudioGraphNodePortGroup) to [MultiCrossfaderGroup](MultiCrossfaderGroup).  |
| MultiCrossfaderGroup([DataContainer](/vext/ref/cls/shr/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/cls/shr/datacontainer) to [MultiCrossfaderGroup](MultiCrossfaderGroup). |

## Properties

| Name          | Type                                     | Description |
| ------------- | ---------------------------------------- | ----------- |
| amplitude     | [AudioGraphNodePort](AudioGraphNodePort) |             |
| start         | [AudioGraphNodePort](AudioGraphNodePort) |             |
| stop          | [AudioGraphNodePort](AudioGraphNodePort) |             |
| fadeAmplitude | number                                   |             |
| fadeBegin     | number                                   |             |
| fadeEnd       | number                                   |             |
| fadeType      | [FaderType](FaderType)                   |             |

## Methods

| Type                                         | Name            | Parameters                                     |
| -------------------------------------------- | --------------- | ---------------------------------------------- |
| [MultiCrossfaderGroup](MultiCrossfaderGroup) | [Clone](#clone) | \[[Guid](/vext/ref/cls/shr/guid) **guid**\] |

### Clone

> [MultiCrossfaderGroup](MultiCrossfaderGroup) **Clone**(\[[Guid](/vext/ref/cls/shr/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |