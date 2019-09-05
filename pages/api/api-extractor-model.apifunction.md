---
layout: page
navigation_source: api_nav
improve_this_button: false
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@microsoft/api-extractor-model](./api-extractor-model.md) &gt; [ApiFunction](./api-extractor-model.apifunction.md)

## ApiFunction class

Represents a TypeScript function declaration.

<b>Signature:</b>

```typescript
export declare class ApiFunction extends ApiFunction_base 
```

## Constructors

|  Constructor | Modifiers | Description |
|  --- | --- | --- |
|  [(constructor)(options)](./api-extractor-model.apifunction._constructor_.md) |  | Constructs a new instance of the <code>ApiFunction</code> class |

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [containerKey](./api-extractor-model.apifunction.containerkey.md) |  | <code>string</code> |  |
|  [kind](./api-extractor-model.apifunction.kind.md) |  | <code>ApiItemKind</code> |  |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [buildCanonicalReference()](./api-extractor-model.apifunction.buildcanonicalreference.md) |  | <b><i>(BETA)</i></b> |
|  [getContainerKey(name, overloadIndex)](./api-extractor-model.apifunction.getcontainerkey.md) | <code>static</code> |  |

## Remarks

This is part of the [ApiModel](./api-extractor-model.apimodel.md) hierarchy of classes, which are serializable representations of API declarations.

`ApiFunction` represents a TypeScript declaration such as this example:

```ts
export function getAverage(x: number, y: number): number {
  return (x + y) / 2.0;
}

```
Functions are exported by an entry point module or by a namespace. Compare with [ApiMethod](./api-extractor-model.apimethod.md)<!-- -->, which represents a function that is a member of a class.
