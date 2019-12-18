---
title: TreeBase (Frostbite Container)
---
### Base Classes

[Asset](Asset)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                         | Description                                                                                             |
| ------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------- |
| TreeBase()                                                          | Create a new instance of this container type.                                                           |
| TreeBase(TreeBase other)                                            | Create a reference copy of an instance of the same type.                                                |
| TreeBase([Asset](Asset) other)                                      | Upcast an instance of type [Asset](Asset) to [TreeBase](TreeBase).                                      |
| TreeBase([DataContainer](/vext/ref/cls/shr/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/cls/shr/datacontainer) to [TreeBase](TreeBase). |

## Methods

| Type                 | Name            | Parameters                                     |
| -------------------- | --------------- | ---------------------------------------------- |
| [TreeBase](TreeBase) | [Clone](#clone) | \[[Guid](/vext/ref/cls/shr/guid) **guid**\] |

### Clone

> [TreeBase](TreeBase) **Clone**(\[[Guid](/vext/ref/cls/shr/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |