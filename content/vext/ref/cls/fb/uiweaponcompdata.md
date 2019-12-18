---
title: UIWeaponCompData (Frostbite Container)
---
### Base Classes

[UIComponentData](UIComponentData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                 | Description                                                                                                             |
| --------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- |
| UIWeaponCompData()                                                          | Create a new instance of this container type.                                                                           |
| UIWeaponCompData(UIWeaponCompData other)                                    | Create a reference copy of an instance of the same type.                                                                |
| UIWeaponCompData([UIComponentData](UIComponentData) other)                  | Upcast an instance of type [UIComponentData](UIComponentData) to [UIWeaponCompData](UIWeaponCompData).                  |
| UIWeaponCompData([Asset](Asset) other)                                      | Upcast an instance of type [Asset](Asset) to [UIWeaponCompData](UIWeaponCompData).                                      |
| UIWeaponCompData([DataContainer](/vext/ref/cls/shr/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/cls/shr/datacontainer) to [UIWeaponCompData](UIWeaponCompData). |

## Properties

| Name                    | Type   | Description |
| ----------------------- | ------ | ----------- |
| minHitIndicatorLimit    | number |             |
| maxHitIndicatorLimit    | number |             |
| normalHitIndicatorLimit | number |             |

## Methods

| Type                                 | Name            | Parameters                                     |
| ------------------------------------ | --------------- | ---------------------------------------------- |
| [UIWeaponCompData](UIWeaponCompData) | [Clone](#clone) | \[[Guid](/vext/ref/cls/shr/guid) **guid**\] |

### Clone

> [UIWeaponCompData](UIWeaponCompData) **Clone**(\[[Guid](/vext/ref/cls/shr/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |