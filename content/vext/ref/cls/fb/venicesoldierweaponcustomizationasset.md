---
title: VeniceSoldierWeaponCustomizationAsset (Frostbite Container)
---
### Base Classes

[SoldierWeaponCustomizationAsset](SoldierWeaponCustomizationAsset)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                                                     | Description                                                                                                                                                                      |
| --------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| VeniceSoldierWeaponCustomizationAsset()                                                                         | Create a new instance of this container type.                                                                                                                                    |
| VeniceSoldierWeaponCustomizationAsset(VeniceSoldierWeaponCustomizationAsset other)                              | Create a reference copy of an instance of the same type.                                                                                                                         |
| VeniceSoldierWeaponCustomizationAsset([SoldierWeaponCustomizationAsset](SoldierWeaponCustomizationAsset) other) | Upcast an instance of type [SoldierWeaponCustomizationAsset](SoldierWeaponCustomizationAsset) to [VeniceSoldierWeaponCustomizationAsset](VeniceSoldierWeaponCustomizationAsset). |
| VeniceSoldierWeaponCustomizationAsset([Asset](Asset) other)                                                     | Upcast an instance of type [Asset](Asset) to [VeniceSoldierWeaponCustomizationAsset](VeniceSoldierWeaponCustomizationAsset).                                                     |
| VeniceSoldierWeaponCustomizationAsset([DataContainer](/vext/ref/cls/shr/datacontainer) other)                | Upcast an instance of type [DataContainer](/vext/ref/cls/shr/datacontainer) to [VeniceSoldierWeaponCustomizationAsset](VeniceSoldierWeaponCustomizationAsset).                |

## Methods

| Type                                                                           | Name            | Parameters                                     |
| ------------------------------------------------------------------------------ | --------------- | ---------------------------------------------- |
| [VeniceSoldierWeaponCustomizationAsset](VeniceSoldierWeaponCustomizationAsset) | [Clone](#clone) | \[[Guid](/vext/ref/cls/shr/guid) **guid**\] |

### Clone

> [VeniceSoldierWeaponCustomizationAsset](VeniceSoldierWeaponCustomizationAsset) **Clone**(\[[Guid](/vext/ref/cls/shr/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |