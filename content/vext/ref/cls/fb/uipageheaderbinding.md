---
title: UIPageHeaderBinding (Frostbite Container)
---
### Base Classes

[UIDataBinding](UIDataBinding)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                    | Description                                                                                                                   |
| ------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------- |
| UIPageHeaderBinding()                                                          | Create a new instance of this container type.                                                                                 |
| UIPageHeaderBinding(UIPageHeaderBinding other)                                 | Create a reference copy of an instance of the same type.                                                                      |
| UIPageHeaderBinding([UIDataBinding](UIDataBinding) other)                      | Upcast an instance of type [UIDataBinding](UIDataBinding) to [UIPageHeaderBinding](UIPageHeaderBinding).                      |
| UIPageHeaderBinding([DataContainer](/vext/ref/cls/shr/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/cls/shr/datacontainer) to [UIPageHeaderBinding](UIPageHeaderBinding). |

## Properties

| Name                 | Type                                                       | Description |
| -------------------- | ---------------------------------------------------------- | ----------- |
| header               | [UIDataSourceInfo](UIDataSourceInfo)                       |             |
| subHeader            | [UIDataSourceInfo](UIDataSourceInfo)                       |             |
| icon                 | [UIDataSourceInfo](UIDataSourceInfo)                       |             |
| staticHeader         | string                                                     |             |
| staticSubHeader      | string                                                     |             |
| staticIcon           | string                                                     |             |
| levelSpecificHeaders | [UILevelSpecificPageHeader](UILevelSpecificPageHeader)\[\] |             |

## Methods

| Type                                       | Name            | Parameters                                     |
| ------------------------------------------ | --------------- | ---------------------------------------------- |
| [UIPageHeaderBinding](UIPageHeaderBinding) | [Clone](#clone) | \[[Guid](/vext/ref/cls/shr/guid) **guid**\] |

### Clone

> [UIPageHeaderBinding](UIPageHeaderBinding) **Clone**(\[[Guid](/vext/ref/cls/shr/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |