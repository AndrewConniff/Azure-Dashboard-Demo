# Azure Dashboard Demo

![project image](https://az400assets.blob.core.windows.net/dashboard-markdown/img1.png)

You can use any combination of plain text, Markdown syntax, and HTML content on the markdown tile. The Azure portal uses an open-source library called [marked](https://marked.js.org/) to transform your content into HTML that is shown on the tile.

## Avoid

- JavaScript – script tags and inline JavaScript evaluations will be removed.
- iframes - ifram tags will be removed.
- Style - style tags will be removed.

    *Inline style attributes on HTML elements aren't officially supported. You may find that some inline style elements work for you, but if they interfere with the layout of the portal, they could stop working at any time. The Markdown tile is intended for basic, static content that uses the default styles of the portal.*

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

### Use HTML for tables

<table>
    <caption>Most Popular Content Management Systems</caption>
    <thead>
        <tr>
            <th>CMS</th>
            <th>Usage *</th>
            <th>Change Since Jan 1</th>
            <th>Market Share *</th>
            <th>Change Since Jan 1</th>
        </tr>
    </thead>
    <tfoot>
        <tr>
            <td>Totals</td>
            <td>33.3%</td>
            <td></td>
            <td>76%</td>
            <td></td>
        </tr>
        <tr>
            <td colspan="5">* <strong>Usage</strong> is percentage of surveyed websites 
            that use the associated CMS. <strong>Market Share</strong> is the percentage 
            of surveyed websites powered by a CMS that use the associated CMS. For example, 
            25.8% of all surveyed websites use WordPress, and WordPress commands 59.1% 
            market share of the total CMS market.</td>
        </tr>
        <tr>
            <td colspan="5">The data in this table is provided courtesy of 
            <a href="http://w3techs.com" target="_blank">W3Techs</a> and was captured in 
            February 2016. To learn more about this topic visit the 
            <a href="http://w3techs.com/technologies/overview/content_management/all" 
            target="_blank">overview of content management systems</a> from W3Techs.</td>
        </tr>
    </tfoot>
    <tbody>
        <tr>
            <td>WordPress</td>
            <td>25.8%</td>
            <td>+0.2%</td>
            <td>59.1%</td>
            <td>+0.3%</td>
        </tr>
        <tr>
            <td>Joomla</td>
            <td>2.8%</td>
            <td>No Change</td>
            <td>6.4%</td>
            <td rowspan="4">No Change</td>
        </tr>
        <tr>
            <td>Drupal</td>
            <td>2.2%</td>
            <td>+0.1%</td>
            <td>4.9%</td>
            <!--Deleted td element to be collapsed with rowspan-->
        </tr>
        <tr>
            <td>Magento</td>
            <td>1.3%</td>
            <td>+0.1%</td>
            <td>2.9%</td>
            <!--Deleted td element to be collapsed with rowspan-->
        </tr>
        <tr>
            <td>Blogger</td>
            <td>1.2%</td>
            <td>No Change</td>
            <td>2.7%</td>
            <!--Deleted td element to be collapsed with rowspan-->
        </tr>
    </tbody>
</table>


Read more: https://html.com/tables/tutorial/#ixzz6XEEja5R7