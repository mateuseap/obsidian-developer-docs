<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [obsidian](./obsidian.md) &gt; [MetadataCache](./obsidian.metadatacache.md) &gt; [on](./obsidian.metadatacache.on_2.md)

## MetadataCache.on() method

Called when a file has been resolved for `resolvedLinks` and `unresolvedLinks`<!-- -->. This happens sometimes after a file has been indexed.

**Signature:**

```typescript
on(name: 'resolve', callback: (file: TFile) => any, ctx?: any): EventRef;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  name | 'resolve' |  |
|  callback | (file: [TFile](./obsidian.tfile.md)<!-- -->) =&gt; any |  |
|  ctx | any | _(Optional)_ |

**Returns:**

[EventRef](./obsidian.eventref.md)
