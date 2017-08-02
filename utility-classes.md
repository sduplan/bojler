---
# Page settings
layout: default
keywords: email, css, html, framework, boilerplate, grid, campaigns, templates, bojler, slicejack
comments: false

# Hero section
title: Utility classes
description: High-specificity, very explicit selectors and helper classes. We use them to easily manipulate with things such as alignments and images.

# Micro navigation
micro_nav: true

# Page navigation
page_nav:
    prev:
        content: Grid system
        url: /grid-system
    next:
        content: Components
        url: /components
---

## Alignment
### Text alignment
Easily realign text to components with text alignment classes:
- Left: `.align-left`
- Right: `.align-center`
- Center: `.align-right`

<div class="example">
    <a href="examples/example-utility-alignment.html" target="blank">Preview</a>
</div>
```html
<table class="container" width="600" align="center" border="0" cellpadding="0" cellspacing="0">
    <tr>
        <td class="column-12 first last">
            <table class="table-full-width" width="100%" border="0" cellpadding="0" cellspacing="0">
                <tr>
                    <td class="align-left">Align left</td>
                </tr>
                <tr>
                    <td class="align-center">Align center</td>
                </tr>
                <tr>
                    <td class="align-right">Align right</td>
                </tr>
            </table>
        </td><!-- /.col -->
    </tr>
</table><!-- /.container -->
```

### Yahoo! Mail
This class helps you to fix centering issues for elements in Yahoo! Mail email client:
- Center: `.yahoo-center`

## Images
We've implemented images reset class which you can use to reset images  
`font-size` and `line-height` to display properly on some Outlook email clients.
