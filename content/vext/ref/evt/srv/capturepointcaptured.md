---
title: CapturePoint:Captured (Server Event)
---
## Description

## Parameters

| Type                                  | Name         | Description |
| ------------------------------------- | ------------ | ----------- |
| [Entity](/vext/ref/cls/shr/entity) | capturePoint |             |

## Usage Example

``` lua
local function OnCapturePointCaptured(capturePoint)
    -- Add your logic here
end

Events:Subscribe('CapturePoint:Captured', OnCapturePointCaptured)
```