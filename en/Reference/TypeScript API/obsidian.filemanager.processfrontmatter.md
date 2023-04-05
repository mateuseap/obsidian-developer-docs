<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [obsidian](./obsidian.md) &gt; [FileManager](./obsidian.filemanager.md) &gt; [processFrontMatter](./obsidian.filemanager.processfrontmatter.md)

## FileManager.processFrontMatter() method

Atomically read, modify, and save the frontmatter of a note. The frontmatter is passed in as a JS object, and should be mutated directly to achieve the desired result.

Remember to handle errors thrown by this method.

**Signature:**

```typescript
processFrontMatter(file: TFile, fn: (frontMatter: any) => void): Promise<void>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  file | [TFile](./obsidian.tfile.md) | the file to be modified. Must be a markdown file. |
|  fn | (frontMatter: any) =&gt; void | a callback function which mutates the frontMatter object synchronously. |

**Returns:**

Promise&lt;void&gt;

## Exceptions

YAMLParseError if the YAML parsing fails

any errors that your callback function throws
