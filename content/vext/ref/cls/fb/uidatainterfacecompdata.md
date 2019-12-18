---
title: UIDataInterfaceCompData (Frostbite Container)
---
### Base Classes

[UIComponentData](UIComponentData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                        | Description                                                                                                                           |
| ---------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| UIDataInterfaceCompData()                                                          | Create a new instance of this container type.                                                                                         |
| UIDataInterfaceCompData(UIDataInterfaceCompData other)                             | Create a reference copy of an instance of the same type.                                                                              |
| UIDataInterfaceCompData([UIComponentData](UIComponentData) other)                  | Upcast an instance of type [UIComponentData](UIComponentData) to [UIDataInterfaceCompData](UIDataInterfaceCompData).                  |
| UIDataInterfaceCompData([Asset](Asset) other)                                      | Upcast an instance of type [Asset](Asset) to [UIDataInterfaceCompData](UIDataInterfaceCompData).                                      |
| UIDataInterfaceCompData([DataContainer](/vext/ref/cls/shr/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/cls/shr/datacontainer) to [UIDataInterfaceCompData](UIDataInterfaceCompData). |

## Methods

| Type                                               | Name            | Parameters                                     |
| -------------------------------------------------- | --------------- | ---------------------------------------------- |
| [UIDataInterfaceCompData](UIDataInterfaceCompData) | [Clone](#clone) | \[[Guid](/vext/ref/cls/shr/guid) **guid**\] |

### Clone

> [UIDataInterfaceCompData](UIDataInterfaceCompData) **Clone**(\[[Guid](/vext/ref/cls/shr/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |