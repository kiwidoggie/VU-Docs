---
title: CapturePoint:Lost (Server Event)
---
## Description

## Parameters

| Type                                  | Name         | Description |
| ------------------------------------- | ------------ | ----------- |
| [Entity](/vext/ref/cls/shr/entity) | capturePoint |             |

## Usage Example

``` lua
local function OnCapturePointLost(capturePoint)
    -- Add your logic here
end

Events:Subscribe('CapturePoint:Lost', OnCapturePointLost)
```