---
title: EndPointData
---

## Summary

### Constructors

|  |
| --- |
| **[EndPointData](#constructor-0)**() |
| **[EndPointData](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "pos" >}} | float |
| {{< prop "endDamping" >}} | float |
| {{< prop "springLength" >}} | float |
| {{< prop "springAcceleration" >}} | float |
| {{< prop "springDamping" >}} | float |

### Methods

| Method | Returns |
| ------ | ------- |
| **[Clone](#clone)**() | [EndPointData](/vext/ref/fb/endpointdata) |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "EndPointData" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### EndPointData {#constructor-0}

> **EndPointData**()

Creates a new [EndPointData](/vext/ref/fb/endpointdata) frostbite instance.

### EndPointData {#constructor-1}

> **EndPointData**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [EndPointData](/vext/ref/fb/endpointdata) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

## Properties

### {{% prop-heading "pos" %}}

> **float**

### {{% prop-heading "endDamping" %}}

> **float**

### {{% prop-heading "springLength" %}}

> **float**

### {{% prop-heading "springAcceleration" %}}

> **float**

### {{% prop-heading "springDamping" %}}

> **float**

## Methods

### Clone {#clone}

> **Clone**(): [EndPointData](/vext/ref/fb/endpointdata)

Creates a shallow-copy clone of this structure, which is essentially the equivalent of creating a new structure of the same type and assigning the values of this structure to all of its properties. Any properties that contain structure types (eg. [Vec3](/vext/ref/shared/type/vec3)) will be cloned when assigning, while properties that contain instance types (eg. [DataContainer](/vext/ref/shared/type/datacontainer)) will be referencing the same instance.

#### Returns

| Type | Description |
| ---- | ----------- |
| **[EndPointData](/vext/ref/fb/endpointdata)** | The newly created structure. |

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [EndPointData](/vext/ref/fb/endpointdata) type.

