---
title: UIMatchCompData
---
### Base Classes

[UIComponentData](UIComponentData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                | Description                                                                                                           |
| -------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------- |
| UIMatchCompData()                                                          | Create a new instance of this container type.                                                                         |
| UIMatchCompData(UIMatchCompData other)                                     | Create a reference copy of an instance of the same type.                                                              |
| UIMatchCompData([UIComponentData](UIComponentData) other)                  | Upcast an instance of type [UIComponentData](UIComponentData) to [UIMatchCompData](UIMatchCompData).                  |
| UIMatchCompData([Asset](Asset) other)                                      | Upcast an instance of type [Asset](Asset) to [UIMatchCompData](UIMatchCompData).                                      |
| UIMatchCompData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [UIMatchCompData](UIMatchCompData). |

## Methods

| Type                               | Name            | Parameters                                     |
| ---------------------------------- | --------------- | ---------------------------------------------- |
| [UIMatchCompData](UIMatchCompData) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [UIMatchCompData](UIMatchCompData) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |