---
layout: page
navigation_source: api_nav
improve_this_button: false
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@microsoft/rush-lib](./rush-lib.md) &gt; [VersionPolicy](./rush-lib.versionpolicy.md) &gt; [ensure](./rush-lib.versionpolicy.ensure.md)

## VersionPolicy.ensure() method

> This API is provided as a preview for developers and may change based on feedback that we receive. Do not use this API in a production environment.
> 

Returns an updated package json that satisfies the policy.

<b>Signature:</b>

```typescript
abstract ensure(project: IPackageJson, force?: boolean): IPackageJson | undefined;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  project | <code>IPackageJson</code> | package json |
|  force | <code>boolean</code> | force update even when the project version is higher than the policy version. |

<b>Returns:</b>

`IPackageJson | undefined`
