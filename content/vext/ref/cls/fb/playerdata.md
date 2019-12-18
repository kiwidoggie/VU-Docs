---
title: PlayerData (Frostbite Container)
---
### Base Classes

[Asset](Asset)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                           | Description                                                                                                 |
| --------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------- |
| PlayerData()                                                          | Create a new instance of this container type.                                                               |
| PlayerData(PlayerData other)                                          | Create a reference copy of an instance of the same type.                                                    |
| PlayerData([Asset](Asset) other)                                      | Upcast an instance of type [Asset](Asset) to [PlayerData](PlayerData).                                      |
| PlayerData([DataContainer](/vext/ref/cls/shr/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/cls/shr/datacontainer) to [PlayerData](PlayerData). |

## Properties

| Name                   | Type                                                 | Description |
| ---------------------- | ---------------------------------------------------- | ----------- |
| playerView             | [PlayerViewData](PlayerViewData)                     |             |
| inputConceptDefinition | [EntryInputActionMapsData](EntryInputActionMapsData) |             |
| inputMapping           | [InputActionMappingsData](InputActionMappingsData)   |             |

## Methods

| Type                     | Name            | Parameters                                     |
| ------------------------ | --------------- | ---------------------------------------------- |
| [PlayerData](PlayerData) | [Clone](#clone) | \[[Guid](/vext/ref/cls/shr/guid) **guid**\] |

### Clone

> [PlayerData](PlayerData) **Clone**(\[[Guid](/vext/ref/cls/shr/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |