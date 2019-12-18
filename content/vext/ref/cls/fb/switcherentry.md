---
title: SwitcherEntry (Frostbite Container)
---
### Base Classes

[AudioGraphNodePortGroup](AudioGraphNodePortGroup)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                              | Description                                                                                                       |
| ------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------- |
| SwitcherEntry()                                                          | Create a new instance of this container type.                                                                     |
| SwitcherEntry(SwitcherEntry other)                                       | Create a reference copy of an instance of the same type.                                                          |
| SwitcherEntry([AudioGraphNodePortGroup](AudioGraphNodePortGroup) other)  | Upcast an instance of type [AudioGraphNodePortGroup](AudioGraphNodePortGroup) to [SwitcherEntry](SwitcherEntry).  |
| SwitcherEntry([DataContainer](/vext/ref/cls/shr/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/cls/shr/datacontainer) to [SwitcherEntry](SwitcherEntry). |

## Properties

| Name        | Type                                     | Description |
| ----------- | ---------------------------------------- | ----------- |
| caseTrigger | [AudioGraphNodePort](AudioGraphNodePort) |             |
| caseValue   | number                                   |             |

## Methods

| Type                           | Name            | Parameters                                     |
| ------------------------------ | --------------- | ---------------------------------------------- |
| [SwitcherEntry](SwitcherEntry) | [Clone](#clone) | \[[Guid](/vext/ref/cls/shr/guid) **guid**\] |

### Clone

> [SwitcherEntry](SwitcherEntry) **Clone**(\[[Guid](/vext/ref/cls/shr/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |