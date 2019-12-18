---
title: AntTrackData (Frostbite Container)
---
### Base Classes

[CustomSequenceTrackData](CustomSequenceTrackData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                             | Description                                                                                                     |
| ----------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- |
| AntTrackData()                                                          | Create a new instance of this container type.                                                                   |
| AntTrackData(AntTrackData other)                                        | Create a reference copy of an instance of the same type.                                                        |
| AntTrackData([CustomSequenceTrackData](CustomSequenceTrackData) other)  | Upcast an instance of type [CustomSequenceTrackData](CustomSequenceTrackData) to [AntTrackData](AntTrackData).  |
| AntTrackData([EntityData](EntityData) other)                            | Upcast an instance of type [EntityData](EntityData) to [AntTrackData](AntTrackData).                            |
| AntTrackData([GameObjectData](GameObjectData) other)                    | Upcast an instance of type [GameObjectData](GameObjectData) to [AntTrackData](AntTrackData).                    |
| AntTrackData([GameDataContainer](GameDataContainer) other)              | Upcast an instance of type [GameDataContainer](GameDataContainer) to [AntTrackData](AntTrackData).              |
| AntTrackData([DataContainer](/vext/ref/cls/shr/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/cls/shr/datacontainer) to [AntTrackData](AntTrackData). |

## Properties

| Name              | Type                                     | Description |
| ----------------- | ---------------------------------------- | ----------- |
| antTrackItemDatas | [AntTrackItemData](AntTrackItemData)\[\] |             |

## Methods

| Type                         | Name            | Parameters                                     |
| ---------------------------- | --------------- | ---------------------------------------------- |
| [AntTrackData](AntTrackData) | [Clone](#clone) | \[[Guid](/vext/ref/cls/shr/guid) **guid**\] |

### Clone

> [AntTrackData](AntTrackData) **Clone**(\[[Guid](/vext/ref/cls/shr/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |