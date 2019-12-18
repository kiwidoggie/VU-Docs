---
title: UIStoreCompData (Frostbite Container)
---
### Base Classes

[UIComponentData](UIComponentData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                | Description                                                                                                           |
| -------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------- |
| UIStoreCompData()                                                          | Create a new instance of this container type.                                                                         |
| UIStoreCompData(UIStoreCompData other)                                     | Create a reference copy of an instance of the same type.                                                              |
| UIStoreCompData([UIComponentData](UIComponentData) other)                  | Upcast an instance of type [UIComponentData](UIComponentData) to [UIStoreCompData](UIStoreCompData).                  |
| UIStoreCompData([Asset](Asset) other)                                      | Upcast an instance of type [Asset](Asset) to [UIStoreCompData](UIStoreCompData).                                      |
| UIStoreCompData([DataContainer](/vext/ref/cls/shr/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/cls/shr/datacontainer) to [UIStoreCompData](UIStoreCompData). |

## Methods

| Type                               | Name            | Parameters                                     |
| ---------------------------------- | --------------- | ---------------------------------------------- |
| [UIStoreCompData](UIStoreCompData) | [Clone](#clone) | \[[Guid](/vext/ref/cls/shr/guid) **guid**\] |

### Clone

> [UIStoreCompData](UIStoreCompData) **Clone**(\[[Guid](/vext/ref/cls/shr/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |