---
layout: page
navigation_source: api_nav
improve_this_button: false
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/rig-package](./rig-package.md) &gt; [RigConfig](./rig-package.rigconfig.md) &gt; [getResolvedProfileFolder](./rig-package.rigconfig.getresolvedprofilefolder.md)

## RigConfig.getResolvedProfileFolder() method

Performs Node.js module resolution to locate the rig package folder, then returns the absolute path of the rig profile folder specified by `rig.json`<!-- -->.

<b>Signature:</b>

```typescript
getResolvedProfileFolder(): string;
```
<b>Returns:</b>

string

## Remarks

If no `rig.json` file was found, then this method throws an error.

Example: `/path/to/your-project/node_modules/example-rig/profiles/example-profile`

