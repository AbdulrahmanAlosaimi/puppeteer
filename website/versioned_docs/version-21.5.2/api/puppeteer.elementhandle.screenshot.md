---
sidebar_label: ElementHandle.screenshot
---

# ElementHandle.screenshot() method

This method scrolls element into view if needed, and then uses [Page.screenshot()](./puppeteer.page.screenshot_1.md) to take a screenshot of the element. If the element is detached from DOM, the method throws an error.

#### Signature:

```typescript
class ElementHandle {
  screenshot(
    options: Readonly<ScreenshotOptions> & {
      encoding: 'base64';
    }
  ): Promise<string>;
}
```

## Parameters

| Parameter | Type                                                                                                | Description |
| --------- | --------------------------------------------------------------------------------------------------- | ----------- |
| options   | Readonly&lt;[ScreenshotOptions](./puppeteer.screenshotoptions.md)&gt; &amp; \{ encoding: 'base64'; \} |             |

**Returns:**

Promise&lt;string&gt;
