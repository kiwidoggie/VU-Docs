---
title: SoundDataChunk (Frostbite Structure)
---
## Description

A structure type representing a Frostbite data type.

## Constructors

| Constructor                          | Description                                              |
| ------------------------------------ | -------------------------------------------------------- |
| SoundDataChunk()                     | Create a new instance of this structure type.            |
| SoundDataChunk(SoundDataChunk other) | Create a reference copy of a structure of the same type. |

## Properties

| Name      | Type                              | Description |
| --------- | --------------------------------- | ----------- |
| chunkId   | [Guid](/vext/ref/cls/shr/Guid) |             |
| chunkSize | number                            |             |

## Methods

| Type                             | Name            | Parameters |
| -------------------------------- | --------------- | ---------- |
| [SoundDataChunk](SoundDataChunk) | [Clone](#clone) |            |

### Clone

> [SoundDataChunk](SoundDataChunk) **Clone**()

Creates a shallow-copy clone of the structure. Works similarly to [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone).