<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Protocol](./puppeteer.protocol.md) &gt; [Browser](./puppeteer.protocol.browser.md) &gt; [SetDownloadBehaviorRequest](./puppeteer.protocol.browser.setdownloadbehaviorrequest.md)

## Protocol.Browser.SetDownloadBehaviorRequest interface

<b>Signature:</b>

```typescript
export interface SetDownloadBehaviorRequest 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [behavior](./puppeteer.protocol.browser.setdownloadbehaviorrequest.behavior.md) | ('deny' \| 'allow' \| 'allowAndName' \| 'default') | Whether to allow all or deny all download requests, or use default Chrome behavior if available (otherwise deny). \|allowAndName\| allows download and names files according to their dowmload guids. (SetDownloadBehaviorRequestBehavior enum) |
|  [browserContextId](./puppeteer.protocol.browser.setdownloadbehaviorrequest.browsercontextid.md) | [BrowserContextID](./puppeteer.protocol.browser.browsercontextid.md) | BrowserContext to set download behavior. When omitted, default browser context is used. |
|  [downloadPath](./puppeteer.protocol.browser.setdownloadbehaviorrequest.downloadpath.md) | string | The default path to save downloaded files to. This is requred if behavior is set to 'allow' or 'allowAndName'. |
