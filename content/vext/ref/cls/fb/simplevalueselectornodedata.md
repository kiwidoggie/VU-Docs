---
title: SimpleValueSelectorNodeData (Frostbite Container)
---
### Base Classes

[AudioGraphNodeData](AudioGraphNodeData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                            | Description                                                                                                                                   |
| -------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| SimpleValueSelectorNodeData()                                                          | Create a new instance of this container type.                                                                                                 |
| SimpleValueSelectorNodeData(SimpleValueSelectorNodeData other)                         | Create a reference copy of an instance of the same type.                                                                                      |
| SimpleValueSelectorNodeData([AudioGraphNodeData](AudioGraphNodeData) other)            | Upcast an instance of type [AudioGraphNodeData](AudioGraphNodeData) to [SimpleValueSelectorNodeData](SimpleValueSelectorNodeData).            |
| SimpleValueSelectorNodeData([DataContainer](/vext/ref/cls/shr/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/cls/shr/datacontainer) to [SimpleValueSelectorNodeData](SimpleValueSelectorNodeData). |

## Properties

| Name      | Type                                     | Description |
| --------- | ---------------------------------------- | ----------- |
| outValues | number\[\]                               |             |
| index     | [AudioGraphNodePort](AudioGraphNodePort) |             |
| out       | [AudioGraphNodePort](AudioGraphNodePort) |             |

## Methods

| Type                                                       | Name            | Parameters                                     |
| ---------------------------------------------------------- | --------------- | ---------------------------------------------- |
| [SimpleValueSelectorNodeData](SimpleValueSelectorNodeData) | [Clone](#clone) | \[[Guid](/vext/ref/cls/shr/guid) **guid**\] |

### Clone

> [SimpleValueSelectorNodeData](SimpleValueSelectorNodeData) **Clone**(\[[Guid](/vext/ref/cls/shr/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |