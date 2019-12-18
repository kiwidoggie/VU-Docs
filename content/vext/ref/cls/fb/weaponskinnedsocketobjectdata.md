---
title: WeaponSkinnedSocketObjectData (Frostbite Container)
---
### Base Classes

[WeaponSocketObjectData](WeaponSocketObjectData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                              | Description                                                                                                                                       |
| ---------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| WeaponSkinnedSocketObjectData()                                                          | Create a new instance of this container type.                                                                                                     |
| WeaponSkinnedSocketObjectData(WeaponSkinnedSocketObjectData other)                       | Create a reference copy of an instance of the same type.                                                                                          |
| WeaponSkinnedSocketObjectData([WeaponSocketObjectData](WeaponSocketObjectData) other)    | Upcast an instance of type [WeaponSocketObjectData](WeaponSocketObjectData) to [WeaponSkinnedSocketObjectData](WeaponSkinnedSocketObjectData).    |
| WeaponSkinnedSocketObjectData([SocketObjectDataBase](SocketObjectDataBase) other)        | Upcast an instance of type [SocketObjectDataBase](SocketObjectDataBase) to [WeaponSkinnedSocketObjectData](WeaponSkinnedSocketObjectData).        |
| WeaponSkinnedSocketObjectData([DataContainer](/vext/ref/cls/shr/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/cls/shr/datacontainer) to [WeaponSkinnedSocketObjectData](WeaponSkinnedSocketObjectData). |

## Methods

| Type                                                           | Name            | Parameters                                     |
| -------------------------------------------------------------- | --------------- | ---------------------------------------------- |
| [WeaponSkinnedSocketObjectData](WeaponSkinnedSocketObjectData) | [Clone](#clone) | \[[Guid](/vext/ref/cls/shr/guid) **guid**\] |

### Clone

> [WeaponSkinnedSocketObjectData](WeaponSkinnedSocketObjectData) **Clone**(\[[Guid](/vext/ref/cls/shr/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |