---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@microsoft/rush-lib](./rush-lib.md) &gt; [ITelemetryOperationResult](./rush-lib.itelemetryoperationresult.md)

## ITelemetryOperationResult interface

> This API is provided as a preview for developers and may change based on feedback that we receive. Do not use this API in a production environment.
> 


**Signature:**

```typescript
export interface ITelemetryOperationResult 
```

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [dependencies](./rush-lib.itelemetryoperationresult.dependencies.md) |  | string\[\] | **_(BETA)_** The names of operations that this operation depends on. |
|  [endTimestampMs?](./rush-lib.itelemetryoperationresult.endtimestampms.md) |  | number | **_(BETA)_** _(Optional)_ A timestamp in milliseconds (from <code>performance.now()</code>) when the operation finished. If the operation was blocked, will be <code>undefined</code>. |
|  [nonCachedDurationMs?](./rush-lib.itelemetryoperationresult.noncacheddurationms.md) |  | number | **_(BETA)_** _(Optional)_ Duration in milliseconds when the operation does not hit cache |
|  [result](./rush-lib.itelemetryoperationresult.result.md) |  | string | **_(BETA)_** The status code for the operation. |
|  [startTimestampMs?](./rush-lib.itelemetryoperationresult.starttimestampms.md) |  | number | **_(BETA)_** _(Optional)_ A timestamp in milliseconds (from <code>performance.now()</code>) when the operation started. If the operation was blocked, will be <code>undefined</code>. |
