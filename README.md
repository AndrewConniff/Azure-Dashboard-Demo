# Azure Dashboard Demo

![project image](https://az400assets.blob.core.windows.net/dashboard-markdown/img1.png)

You can use any combination of plain text, Markdown syntax, and HTML content on the markdown tile. The Azure portal uses an open-source library called [marked](https://marked.js.org/) to transform your content into HTML that is shown on the tile.

## Avoid

JavaScript – \<script> tags and inline JavaScript evaluations will be removed.
iframes - \<iframe> tags will be removed.
Style - \<style> tags will be removed. Inline style attributes on HTML elements aren't officially supported. You may find that some inline style elements work for you, but if they interfere with the layout of the portal, they could stop working at any time. The Markdown tile is intended for basic, static content that uses the default styles of the portal.

## Examples

### Code snippets

```csharp
using system.net

namespace Project Namespace

public async Task<obj> Main(){
   ...
}
```

### Notes

> Note: This is information a reader should notice even when skimming.

You can use links, like this link to the full documentation [here](https://docs.microsoft.com/en-us/azure/azure-portal/azure-portal-markdown-tile)

### Strikethrough

~~The world is flat.~~ We now know that the world is round.
