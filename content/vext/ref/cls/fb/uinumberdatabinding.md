---
title: UINumberDataBinding (Frostbite Container)
---
### Base Classes

[UIDataBinding](UIDataBinding)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                    | Description                                                                                                                   |
| ------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------- |
| UINumberDataBinding()                                                          | Create a new instance of this container type.                                                                                 |
| UINumberDataBinding(UINumberDataBinding other)                                 | Create a reference copy of an instance of the same type.                                                                      |
| UINumberDataBinding([UIDataBinding](UIDataBinding) other)                      | Upcast an instance of type [UIDataBinding](UIDataBinding) to [UINumberDataBinding](UINumberDataBinding).                      |
| UINumberDataBinding([DataContainer](/vext/ref/cls/shr/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/cls/shr/datacontainer) to [UINumberDataBinding](UINumberDataBinding). |

## Properties

| Name     | Type                                 | Description |
| -------- | ------------------------------------ | ----------- |
| value    | [UIDataSourceInfo](UIDataSourceInfo) |             |
| numValue | number                               |             |
| refresh  | bool                                 |             |

## Methods

| Type                                       | Name            | Parameters                                     |
| ------------------------------------------ | --------------- | ---------------------------------------------- |
| [UINumberDataBinding](UINumberDataBinding) | [Clone](#clone) | \[[Guid](/vext/ref/cls/shr/guid) **guid**\] |

### Clone

> [UINumberDataBinding](UINumberDataBinding) **Clone**(\[[Guid](/vext/ref/cls/shr/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |