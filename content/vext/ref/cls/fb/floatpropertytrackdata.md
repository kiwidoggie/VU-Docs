---
title: FloatPropertyTrackData (Frostbite Container)
---
### Base Classes

[SimplePropertyTrackData](SimplePropertyTrackData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                       | Description                                                                                                                         |
| --------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| FloatPropertyTrackData()                                                          | Create a new instance of this container type.                                                                                       |
| FloatPropertyTrackData(FloatPropertyTrackData other)                              | Create a reference copy of an instance of the same type.                                                                            |
| FloatPropertyTrackData([SimplePropertyTrackData](SimplePropertyTrackData) other)  | Upcast an instance of type [SimplePropertyTrackData](SimplePropertyTrackData) to [FloatPropertyTrackData](FloatPropertyTrackData).  |
| FloatPropertyTrackData([PropertyTrackData](PropertyTrackData) other)              | Upcast an instance of type [PropertyTrackData](PropertyTrackData) to [FloatPropertyTrackData](FloatPropertyTrackData).              |
| FloatPropertyTrackData([DataContainer](/vext/ref/cls/shr/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/cls/shr/datacontainer) to [FloatPropertyTrackData](FloatPropertyTrackData). |

## Properties

| Name   | Type       | Description |
| ------ | ---------- | ----------- |
| values | number\[\] |             |

## Methods

| Type                                             | Name            | Parameters                                     |
| ------------------------------------------------ | --------------- | ---------------------------------------------- |
| [FloatPropertyTrackData](FloatPropertyTrackData) | [Clone](#clone) | \[[Guid](/vext/ref/cls/shr/guid) **guid**\] |

### Clone

> [FloatPropertyTrackData](FloatPropertyTrackData) **Clone**(\[[Guid](/vext/ref/cls/shr/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |