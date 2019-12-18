---
title: BasicDogTagData (Frostbite Container)
---
### Base Classes

[DogTagData](DogTagData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                | Description                                                                                                           |
| -------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------- |
| BasicDogTagData()                                                          | Create a new instance of this container type.                                                                         |
| BasicDogTagData(BasicDogTagData other)                                     | Create a reference copy of an instance of the same type.                                                              |
| BasicDogTagData([DogTagData](DogTagData) other)                            | Upcast an instance of type [DogTagData](DogTagData) to [BasicDogTagData](BasicDogTagData).                            |
| BasicDogTagData([UnlockAssetBase](UnlockAssetBase) other)                  | Upcast an instance of type [UnlockAssetBase](UnlockAssetBase) to [BasicDogTagData](BasicDogTagData).                  |
| BasicDogTagData([Asset](Asset) other)                                      | Upcast an instance of type [Asset](Asset) to [BasicDogTagData](BasicDogTagData).                                      |
| BasicDogTagData([DataContainer](/vext/ref/cls/shr/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/cls/shr/datacontainer) to [BasicDogTagData](BasicDogTagData). |

## Methods

| Type                               | Name            | Parameters                                     |
| ---------------------------------- | --------------- | ---------------------------------------------- |
| [BasicDogTagData](BasicDogTagData) | [Clone](#clone) | \[[Guid](/vext/ref/cls/shr/guid) **guid**\] |

### Clone

> [BasicDogTagData](BasicDogTagData) **Clone**(\[[Guid](/vext/ref/cls/shr/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |