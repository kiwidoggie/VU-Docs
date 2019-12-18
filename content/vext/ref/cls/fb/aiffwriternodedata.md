---
title: AiffWriterNodeData (Frostbite Container)
---
### Base Classes

[AudioGraphNodeData](AudioGraphNodeData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                   | Description                                                                                                                 |
| ----------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| AiffWriterNodeData()                                                          | Create a new instance of this container type.                                                                               |
| AiffWriterNodeData(AiffWriterNodeData other)                                  | Create a reference copy of an instance of the same type.                                                                    |
| AiffWriterNodeData([AudioGraphNodeData](AudioGraphNodeData) other)            | Upcast an instance of type [AudioGraphNodeData](AudioGraphNodeData) to [AiffWriterNodeData](AiffWriterNodeData).            |
| AiffWriterNodeData([DataContainer](/vext/ref/cls/shr/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/cls/shr/datacontainer) to [AiffWriterNodeData](AiffWriterNodeData). |

## Properties

| Name     | Type                                       | Description |
| -------- | ------------------------------------------ | ----------- |
| inValue  | [AudioGraphNodePort](AudioGraphNodePort)   |             |
| start    | [AudioGraphNodePort](AudioGraphNodePort)   |             |
| stop     | [AudioGraphNodePort](AudioGraphNodePort)   |             |
| plugin   | [SoundGraphPluginRef](SoundGraphPluginRef) |             |
| fileName | string                                     |             |

## Methods

| Type                                     | Name            | Parameters                                     |
| ---------------------------------------- | --------------- | ---------------------------------------------- |
| [AiffWriterNodeData](AiffWriterNodeData) | [Clone](#clone) | \[[Guid](/vext/ref/cls/shr/guid) **guid**\] |

### Clone

> [AiffWriterNodeData](AiffWriterNodeData) **Clone**(\[[Guid](/vext/ref/cls/shr/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |