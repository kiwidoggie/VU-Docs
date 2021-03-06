---
title: GameAnimationConfig
---

Inherits from [Asset](/vext/ref/fb/asset)

## Summary

### Constructors

|  |
| --- |
| **[GameAnimationConfig](#constructor-0)**() |
| **[GameAnimationConfig](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |
| **[GameAnimationConfig](#constructor-2)**(other: [Asset](/vext/ref/fb/asset)) |
| **[GameAnimationConfig](#constructor-3)**(other: [DataContainer](/vext/ref/shared/type/datacontainer)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "serverEnable" >}} | bool |
| {{< prop "clientEnable" >}} | bool |
| {{< prop "useRawGamepadInput" >}} | bool |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "GameAnimationConfig" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### GameAnimationConfig {#constructor-0}

> **GameAnimationConfig**()

Creates a new [GameAnimationConfig](/vext/ref/fb/gameanimationconfig) frostbite instance.

### GameAnimationConfig {#constructor-1}

> **GameAnimationConfig**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [GameAnimationConfig](/vext/ref/fb/gameanimationconfig) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

### GameAnimationConfig {#constructor-2}

> **GameAnimationConfig**(other: [Asset](/vext/ref/fb/asset))

Casts an instance of type [Asset](/vext/ref/fb/asset) to [GameAnimationConfig](/vext/ref/fb/gameanimationconfig). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [Asset](/vext/ref/fb/asset) | The instance to cast to [GameAnimationConfig](/vext/ref/fb/gameanimationconfig). |

### GameAnimationConfig {#constructor-3}

> **GameAnimationConfig**(other: [DataContainer](/vext/ref/shared/type/datacontainer))

Casts an instance of type [DataContainer](/vext/ref/shared/type/datacontainer) to [GameAnimationConfig](/vext/ref/fb/gameanimationconfig). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [DataContainer](/vext/ref/shared/type/datacontainer) | The instance to cast to [GameAnimationConfig](/vext/ref/fb/gameanimationconfig). |

## Properties

### {{% prop-heading "serverEnable" %}}

> **bool**

### {{% prop-heading "clientEnable" %}}

> **bool**

### {{% prop-heading "useRawGamepadInput" %}}

> **bool**

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [GameAnimationConfig](/vext/ref/fb/gameanimationconfig) type.

