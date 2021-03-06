---
TAGS:
---
## Description

class [PointerInfo](/classes/3.1/PointerInfo) extends [PointerInfoBase](/classes/3.1/PointerInfoBase)

This type contains all the data related to a pointer event in Babylon.js.

The event member is an instance of PointerEvent for all types except PointerWheel and is of type MouseWheelEvent when type equals PointerWheel. The different event types can be found in the [PointerEventTypes](/classes/3.1/PointerEventTypes) class.

## Constructor

## new [PointerInfo](/classes/3.1/PointerInfo)(type, event, MouseWheelEvent, pickInfo)



#### Parameters
 | Name | Type | Description
---|---|---|---
 | type | number | 
 | event | PointerEvent or MouseWheelEvent | 
 | pickInfo | Nullable&lt;[PickingInfo](/classes/3.1/PickingInfo)&gt; | 
## Members

### pickInfo : Nullable&lt;[PickingInfo](/classes/3.1/PickingInfo)&gt;


