---
layout:                     default

title:                      Utility classes
description:                High-specificity, very explicit selectors and helper classes. We use them to easily manipulate with things such as tables, alignment and spacing.
keywords:                   boilerplate, grid, email css, email, email boilerplate, email campaigns, email template, bojler, slicejack

page_nav:                   true
page_nav_prev:              true
page_nav_prev_content:      Grid system
page_nav_prev_url:          /grid-system
page_nav_next:              true
page_nav_next_content:      Components
page_nav_next_url:          /components
---

## Table related
Classes used for manipulating with `<table>` element:
- Full width: `.table-full-width`

<div class="callout callout--info">
    <p><strong>Always define width attribute next to table-full-width class!</strong> It is always good to define width next to table-full-width class, Outlook loves width attributes 😄</p>
</div>
<div class="example">
    <a href="examples/example-utility-tables.html" target="blank">Preview</a>
</div>
```html
<table class="container" width="600" align="center" border="0" cellpadding="0" cellspacing="0">
    <tr>
        <td class="column-12 first last">
            <table class="table-full-width" width="100%" border="0" cellpadding="0" cellspacing="0">
                <tr>
                    <td>This table cell is full width!</td>
                </tr>
            </table>
        </td><!-- /.col -->
    </tr>
</table><!-- /.container -->
```

## Alignment
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

## Spacing
Add spacing to your table cells easily:
- Top: `.spacing-top`
- Bottom: `.spacing-bottom`

<div class="example">
    <a href="examples/example-utility-spacing.html" target="blank">Preview</a>
</div>
```html
<table class="container" width="600" align="center" border="0" cellpadding="0" cellspacing="0">
    <tr>
        <td class="column-12 first last">
            <table class="table-full-width" width="100%" border="0" cellpadding="0" cellspacing="0">
                <tr>
                    <td class="spacing-top spacing-bottom">This table cell have spacing top and bottom.</td>
                </tr>
                <tr>
                    <td class="spacing-top spacing-bottom">This table cell have spacing top and bottom.</td>
                </tr>
            </table>
        </td><!-- /.col -->
    </tr>
</table><!-- /.container -->
```
