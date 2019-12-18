---
title: StatsCategoryVehicleWeaponData (Frostbite Container)
---
### Base Classes

[StatsCategoryGuidData](StatsCategoryGuidData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                               | Description                                                                                                                                         |
| ----------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| StatsCategoryVehicleWeaponData()                                                          | Create a new instance of this container type.                                                                                                       |
| StatsCategoryVehicleWeaponData(StatsCategoryVehicleWeaponData other)                      | Create a reference copy of an instance of the same type.                                                                                            |
| StatsCategoryVehicleWeaponData([StatsCategoryGuidData](StatsCategoryGuidData) other)      | Upcast an instance of type [StatsCategoryGuidData](StatsCategoryGuidData) to [StatsCategoryVehicleWeaponData](StatsCategoryVehicleWeaponData).      |
| StatsCategoryVehicleWeaponData([StatsCategoryBaseData](StatsCategoryBaseData) other)      | Upcast an instance of type [StatsCategoryBaseData](StatsCategoryBaseData) to [StatsCategoryVehicleWeaponData](StatsCategoryVehicleWeaponData).      |
| StatsCategoryVehicleWeaponData([TreeNodeBase](TreeNodeBase) other)                        | Upcast an instance of type [TreeNodeBase](TreeNodeBase) to [StatsCategoryVehicleWeaponData](StatsCategoryVehicleWeaponData).                        |
| StatsCategoryVehicleWeaponData([DataContainer](/vext/ref/cls/shr/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/cls/shr/datacontainer) to [StatsCategoryVehicleWeaponData](StatsCategoryVehicleWeaponData). |

## Methods

| Type                                                             | Name            | Parameters                                     |
| ---------------------------------------------------------------- | --------------- | ---------------------------------------------- |
| [StatsCategoryVehicleWeaponData](StatsCategoryVehicleWeaponData) | [Clone](#clone) | \[[Guid](/vext/ref/cls/shr/guid) **guid**\] |

### Clone

> [StatsCategoryVehicleWeaponData](StatsCategoryVehicleWeaponData) **Clone**(\[[Guid](/vext/ref/cls/shr/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |