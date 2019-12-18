---
title: SphereEvaluatorData (Frostbite Container)
---
### Base Classes

[EvaluatorData](EvaluatorData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                    | Description                                                                                                                   |
| ------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------- |
| SphereEvaluatorData()                                                          | Create a new instance of this container type.                                                                                 |
| SphereEvaluatorData(SphereEvaluatorData other)                                 | Create a reference copy of an instance of the same type.                                                                      |
| SphereEvaluatorData([EvaluatorData](EvaluatorData) other)                      | Upcast an instance of type [EvaluatorData](EvaluatorData) to [SphereEvaluatorData](SphereEvaluatorData).                      |
| SphereEvaluatorData([EmitterComponentData](EmitterComponentData) other)        | Upcast an instance of type [EmitterComponentData](EmitterComponentData) to [SphereEvaluatorData](SphereEvaluatorData).        |
| SphereEvaluatorData([DataContainer](/vext/ref/cls/shr/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/cls/shr/datacontainer) to [SphereEvaluatorData](SphereEvaluatorData). |

## Properties

| Name   | Type                              | Description |
| ------ | --------------------------------- | ----------- |
| scale  | [Vec3](/vext/ref/cls/shr/Vec3) |             |
| pivot  | [Vec3](/vext/ref/cls/shr/Vec3) |             |
| radius | number                            |             |

## Methods

| Type                                       | Name            | Parameters                                     |
| ------------------------------------------ | --------------- | ---------------------------------------------- |
| [SphereEvaluatorData](SphereEvaluatorData) | [Clone](#clone) | \[[Guid](/vext/ref/cls/shr/guid) **guid**\] |

### Clone

> [SphereEvaluatorData](SphereEvaluatorData) **Clone**(\[[Guid](/vext/ref/cls/shr/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/cls/shr/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |