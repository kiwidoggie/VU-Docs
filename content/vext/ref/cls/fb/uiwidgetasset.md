---
title: UIWidgetAsset (Frostbite Container)
---
### Base Classes

[UIAsset](UIAsset)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                              | Description                                                                                                       |
| ------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------- |
| UIWidgetAsset()                                                          | Create a new instance of this container type.                                                                     |
| UIWidgetAsset(UIWidgetAsset other)                                       | Create a reference copy of an instance of the same type.                                                          |
| UIWidgetAsset([UIAsset](UIAsset) other)                                  | Upcast an instance of type [UIAsset](UIAsset) to [UIWidgetAsset](UIWidgetAsset).                                  |
| UIWidgetAsset([Asset](Asset) other)                                      | Upcast an instance of type [Asset](Asset) to [UIWidgetAsset](UIWidgetAsset).                                      |
| UIWidgetAsset([DataContainer](/vext/ref/cls/shr/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/cls/shr/datacontainer) to [UIWidgetAsset](UIWidgetAsset). |

## Properties

| Name         | Type                                             | Description |
| ------------ | ------------------------------------------------ | ----------- |
| widgetEvents | [WidgetEventQueryPair](WidgetEventQueryPair)\[\] |             |

## Methods

| Type                           | Name            | Parameters                                     |
| ------------------------------ | --------------- | ---------------------------------------------- |
| [UIWidgetAsset](UIWidgetAsset) | [Clone](#clone) | \[[Guid](/vext/ref/cls/shr/guid) **guid**\] |

### Clone

> [UIWidgetAsset](UIWidgetAsset) **Clone**(\[[Guid](/vext/ref/cls/shr/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |