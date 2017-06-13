---
layout:                     default

title:                      bojler
description:                Bojler is boilerplate and guideline for writing HTML code
                            that will render correctly across each of the most popular email clients.
keywords:                   boilerplate, grid, email css, email,
                            email boilerplate, email campaigns, email template, bojler, slicejack

author_title:               About Slicejack
author_title_url:           https://slicejack.com
author_description:         Global professionals with a decade of experience in
                            digital development services. <br>We design and build great-looking tested email templates — so you don’t have to.

explore_button_content:     Explore docs
github_button_content:      View on GitHub
github_button_url:          https://github.com/Slicejack/bojler
---

## Introduction
Bojler is boilerplate and guideline for writing HTML code that will render correctly across each of the most popular email clients.

If you have experienced email template development then you know how painful it is to build perfect email template that works on all email clients.

To make it easier for you to develop responsive and lightweight email templates we have created Bojler.

## Features
Quick features overview:

<table>
    <thead>
        <tr>
            <th>Feature</th>
            <th>Description</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Reset styles</td>
            <td>This styles are great starting point for your email template development. They fix all well known bugs in various email clients.</td>
        </tr>
        <tr>
            <td>Responsive</td>
            <td>This email boilerplate is responsive and ready for mobile devices and tablets.</td>
        </tr>
        <tr>
            <td>Typography</td>
            <td>Bojler includes simple and easily customized typography for headings, table cells and lists.</td>
        </tr>
        <tr>
            <td>Grid</td>
            <td>Bojler uses 12-column grid with a 600px container.</td>
        </tr>
        <tr>
            <td>Utilities</td>
            <td>High-specificity, very explicit selectors, helper classes.</td>
        </tr>
        <tr>
            <td>Components</td>
            <td>Premade blocks of code ready to use on your custom e-mail template.</td>
        </tr>
        <tr>
            <td>Lite version</td>
            <td>There's lite version of boilerplate available for you. It's without comments so you can use it right out of the box.</td>
        </tr>
        <tr>
            <td>Great compatibility</td>
            <td>We have tested this boilerplate on numerous email clients and devices.</td>
        </tr>
        <tr>
            <td>Well documented code</td>
            <td>Well documented code for easier usage.</td>
        </tr>
        <tr>
            <td>Open source</td>
            <td>All contents of this boilerplate are licensed under the <a href="https://github.com/Slicejack/bojler/blob/master/LICENSE">MIT license</a>.</td>
        </tr>
    </tbody>
</table>

## Getting started
This is some kind of development process that you should follow when developing email templates with Bojler. If you are experienced email developer then you can skip this section.

### Use lite version of boilerplate
First of all we suggest you to use `email-lite.html` for your email development because you should **avoid using comments** in your final email campaign. Else you may get blocked by SPAM filters.

### Follow [this](https://www.campaignmonitor.com/css/) email CSS guide
On [this link](https://www.campaignmonitor.com/css/) you can find a complete breakdown of the CSS support for the top 10 most popular mobile, web and desktop email clients on the planet. It is recommended to use it as often as possible.

### Compress and optimize your images
It’s also a really great idea to try to keep your entire email as small as humanly possible: under 100kb is ideal but not always possible, under 250kb is pretty standard.

Use a compression app like [compressor.io](https://compressor.io/) to cut all your images down to size as much as possible before you send. Slower load times, especially on mobile, can make or break your email if the overall file size is too large.

### Bring your styles inline
Some email clients strip out `<head>` and `<style>` tags from emails, so it's best to have your CSS written inline within your markup. We know that writing inline CSS is time consuming and repetitive, so [Mailchimp](https://mailchimp.com/) built [this conversion tool](https://templates.mailchimp.com/resources/inline-css/) to automatically inline your email's CSS.

### Test your email properly
Before you send your HTML email you should test it properly. We recommend you to use [Litmus](http://litmus.com) or [Email on Acid](https://www.emailonacid.com).

### Send your email properly
Best way to send your HTML email would be using an Email Service Provider (ESP) such as [MailChimp](http://www.mailchimp.com) or [Campaign Monitor](https://www.campaignmonitor.com/). If you’re just running a quick test we recommend you to use [Putsmail](https://putsmail.com/).

## Compatibility
We have tested Bojler on numerous email clients and devices. In table below you can see what's supported:

<table>
    <thead>
        <tr>
            <th>Email clients</th>
            <th>Web email clients</th>
            <th>Mobile devices</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
                Apple Mail 7<br>
                Apple Mail 8<br>
                Outlook 2000<br>
                Outlook 2002<br>
                Outlook 2003<br>
                Outlook 2007<br>
                Outlook 2010<br>
                Outlook 2011<br>
                Outlook 2013<br>
                Outlook 2016
            </td>
            <td>
                Gmail<br>
                Google Apps<br>
                Office 365<br>
                Outlook.com<br>
                Yahoo! Mail
            </td>
            <td>
                Android 4.4<br>
                iPhone 5<br>
                iPhone 6<br>
                iPad<br>
                iPad Mini
            </td>
        </tr>
    </tbody>
</table>

## Typography
Bojler includes simple and easily customized typography for headings, table cells and lists.

### System fonts stack
Bojler defaults to the system font of a particular operating system. This method can boost performance because the browser or e-mail client doesn't have to download any font files, it's using one it already had.

The beauty of system fonts is that it matches what the current OS uses, so it can be a comfortable look.

```css
html,
body,
table,
table td {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif !important;
}
```

### Table cells and headings
We've updated default typography values for all table cells and headings.

Default values are defined in `px` instead of `em` to work properly in all e-mail clients (Different e-mail clients use different baselines, which makes pixel-perfect work near-impossible when using `em`).
<table>
    <thead>
        <tr>
            <th>Element</th>
            <th>Font size</th>
            <th>Line height</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Base <em>(Table cells)</em></td>
            <td>16px</td>
            <td>23px</td>
        </tr>
        <tr>
            <td>Heading 1</td>
            <td>50px</td>
            <td>58px</td>
        </tr>
        <tr>
            <td>Heading 2</td>
            <td>38px</td>
            <td>46px</td>
        </tr>
        <tr>
            <td>Heading 3</td>
            <td>28px</td>
            <td>36px</td>
        </tr>
        <tr>
            <td>Heading 4</td>
            <td>21px</td>
            <td>29px</td>
        </tr>
        <tr>
            <td>Heading 5</td>
            <td>16px</td>
            <td>23px</td>
        </tr>
        <tr>
            <td>Heading 6</td>
            <td>12px</td>
            <td>20px</td>
        </tr>
    </tbody>
</table>

### Lists
Lists will not work properly in Outlook 2007/10/13 unless you wrap them with table cell (`td`) that have class `.have-list`.

Outlook 2007/10/13 don't support padding by default on lists so we have to add it manually.

<div class="example">
    <a href="examples/example-lists.html" target="blank">Preview</a>
</div>
```html
<table border="0" cellpadding="0" cellspacing="0">
    <tr>
        <td class="have-list">
            <ul>
                <li>Item 1</li>
                <li>Item 2</li>
                <li>Item 3</li>
                <li>Item 4</li>
            </ul>
        </td>
    </tr>
</table>
```

## Grid system
Bojler uses 12-column grid with a 600px container. <br>On mobile devices (under 640px wide), columns become full width and stack vertically.

### Media queries
We suggest you to use this media query when building responsive email with our grid.

```css
@media screen and (max-width: 640px) {}
```

### Grid options
See how aspects of this grid work across devices with a handy table.
<table>
    <thead>
        <tr>
            <th></th>
            <th>Small devices (&lt;640px)</th>
            <th>Large devices (&gt;640px)</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Grid behaviour</td>
            <td>Horizontal</td>
            <td>Collapsed</td>
        </tr>
        <tr>
            <td>Container width</td>
            <td>100%</td>
            <td>600px</td>
        </tr>
        <tr>
            <td>Number of columns</td>
            <td colspan="2">12</td>
        </tr>
        <tr>
            <td>Column width</td>
            <td>100%</td>
            <td>50px</td>
        </tr>
        <tr>
            <td>Gutter width</td>
            <td colspan="2">20px <i>(10px on each side of a column)</i></td>
        </tr>
    </tbody>
</table>

### Container
All emails should have a container element. This gives the email a maximum width for email clients on larger screens. It also orients the email in the center.

<div class="example">
    <a href="examples/example-grid-container.html" target="blank">Preview</a>
</div>
```html
<table class="container" width="600" align="center" border="0" cellpadding="0" cellspacing="0">
    <tr>
        <td>Content goes here ...</td>
    </tr>
</table><!-- /.container -->
```

### Columns
Content should be placed within columns, and columns should be placed as `<td>` of your `.container`.
You can define width of the column with classes such as `.column-1`, `.column-2`, `.column-3` etc.
In `.container` you can place max. 12 columns.

<div class="example">
    <a href="examples/example-grid-columns.html" target="blank">Preview</a>
</div>
```html
<table class="container" width="600" align="center" border="0" cellpadding="0" cellspacing="0">
    <tr>
        <td class="column-12 first last">
            <table border="0" cellpadding="0" cellspacing="0">
                <tr>
                    <td>Content goes here ...</td>
                </tr>
            </table>
        </td><!-- /.col -->
    </tr>
</table><!-- /.container -->
```

<div class="example">
    <a href="examples/example-grid-columns-2.html" target="blank">Preview</a>
</div>
```html
<table class="container" width="600" align="center" border="0" cellpadding="0" cellspacing="0">
    <tr>
        <td class="column-6 first">
            <table border="0" cellpadding="0" cellspacing="0">
                <tr>
                    <td>Content goes here ...</td>
                </tr>
            </table>
        </td><!-- /.col -->

        <td class="column-6 last">
            <table border="0" cellpadding="0" cellspacing="0">
                <tr>
                    <td>Content goes here ...</td>
                </tr>
            </table>
        </td><!-- /.col -->
    </tr>
</table><!-- /.container -->
```

<div class="example">
    <a href="examples/example-grid-columns-3.html" target="blank">Preview</a>
</div>
```html
<table class="container" width="600" align="center" border="0" cellpadding="0" cellspacing="0">
    <tr>
        <td class="column-3 first">
            <table border="0" cellpadding="0" cellspacing="0">
                <tr>
                    <td>Content goes here ...</td>
                </tr>
            </table>
        </td><!-- /.col -->

        <td class="column-3">
            <table border="0" cellpadding="0" cellspacing="0">
                <tr>
                    <td>Content goes here ...</td>
                </tr>
            </table>
        </td><!-- /.col -->

        <td class="column-3">
            <table border="0" cellpadding="0" cellspacing="0">
                <tr>
                    <td>Content goes here ...</td>
                </tr>
            </table>
        </td><!-- /.col -->

        <td class="column-3 last">
            <table border="0" cellpadding="0" cellspacing="0">
                <tr>
                    <td>Content goes here ...</td>
                </tr>
            </table>
        </td><!-- /.col -->
    </tr>
</table><!-- /.container -->
```

### First and last classes

The `.first` class adds the appropriate amount of padding-left to space the content away from the container’s edge. The `.last` class is added to your last set of columns in a row to add padding-right to the column. If you have columns in between `.first` and `.last`, these classes are not needed on the middle columns.

The reason these classes exist is that CSS properties like `:last-child` don’t work in most email clients so a class is needed.

<div class="example">
    <a href="examples/example-grid-first-and-last.html" target="blank">Preview</a>
</div>
```html
<table class="container" width="600" align="center" border="0" cellpadding="0" cellspacing="0">
    <tr>
        <td class="column-4 first">
            <table border="0" cellpadding="0" cellspacing="0">
                <tr>
                    <td>Content goes here ...</td>
                </tr>
            </table>
        </td><!-- /.col -->

        <td class="column-4">
            <table border="0" cellpadding="0" cellspacing="0">
                <tr>
                    <td>Content goes here ...</td>
                </tr>
            </table>
        </td><!-- /.col -->

        <td class="column-4 last">
            <table border="0" cellpadding="0" cellspacing="0">
                <tr>
                    <td>Content goes here ...</td>
                </tr>
            </table>
        </td><!-- /.col -->
    </tr>
</table><!-- /.container -->
```

### Columns without gutter

If you need columns without gutter than you should use `.no-gutter` class on your `.container`.

<div class="example">
    <a href="examples/example-grid-no-gutter.html" target="blank">Preview</a>
</div>
```html
<table class="container no-gutter" width="600" align="center" border="0" cellpadding="0" cellspacing="0">
    <tr>
        <td class="column-6">
            <table border="0" cellpadding="0" cellspacing="0">
                <tr>
                    <td>Content goes here ...</td>
                </tr>
            </table>
        </td><!-- /.col -->

        <td class="column-6">
            <table border="0" cellpadding="0" cellspacing="0">
                <tr>
                    <td>Content goes here ...</td>
                </tr>
            </table>
        </td><!-- /.col -->
    </tr>
</table><!-- /.container -->
```

## Utility classes
High-specificity, very explicit selectors, helper classes.

### Table related
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

### Alignment
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

### Spacing
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

## Components
Components are premade blocks of code which you can use to build your own email template. These components are optional and other things don't depend on them.

### Preheader
Preheader is a snippet of copy pulled in from the body of your email and typically displayed underneath the sender name and subject line in a subscriber’s inbox.

It is pulled from the first few lines of text found within an email. Preheader can either be displayed or hidden in the body of your campaign. We decided to hide it.

<div class="callout callout--info">
    <p><strong>Remove it if you don't need it.</strong> Preheader is already included to all boilerplate files, if you don't need it just erase it.</p>
</div>
```html
<table id="preheader" width="0" border="0" cellpadding="0" cellspacing="0">
    <tr>
        <td>Your preheader text goes here. This block should be hidden.</td>
    </tr>
</table><!-- /#preheader -->
```

### Buttons
We have implemented bulletproof buttons that work properly on all e-mail clients.

We've prepared few button variations for you. To apply the variation just add one of the following classes next to your `btn` class:

- Full width: `btn--full-width`
- Rounded: `btn--rounded`
- Green: `btn--green`
- Red: `btn--red`
- Blue: `btn--blue`
- Dark: `btn--dark`

<div class="example">
    <a href="examples/example-buttons.html" target="blank">Preview</a>
</div>
```html
<table class="btn" border="0" cellpadding="0" cellspacing="0">
    <tr>
        <td>
            <a href="#">Click me!</a>
        </td>
    </tr>
</table><!-- /.btn -->

<table class="btn btn--red" border="0" cellpadding="0" cellspacing="0">
    <tr>
        <td>
            <a href="#">Click me!</a>
        </td>
    </tr>
</table><!-- /.btn -->
```

### Hero
Hero is component with background image and content inside it. With this component we're trying to recreate widely popular hero sections seen all around web.

Everything regarding CSS and reset for this component is already implemented inside our `email.html` and `email-lite.html` except markup. You can copy markup from example below.

<div class="callout callout--info">
    <p><strong>Define width and height!</strong> You have to define width and height on hero element, otherwise your hero component will be broken on some Outlook e-mail clients!</p>
    <p>Furthermore, your background image should have the same dimensions as your hero component, otherwise it will be broken on some Outlook e-mail clients.</p>
</div>
<div class="example">
    <a href="examples/example-hero.html" target="blank">Preview</a>
</div>
```html
<table class="container" width="600" align="center" border="0" cellpadding="0" cellspacing="0">
    <tr>
        <td class="hero" width="600" height="350" background="https://dummyimage.com/600x350/d9f0ff/cccccc.jpg">
            <!--[if gte mso 9]>
            <v:rect xmlns:v="urn:schemas-microsoft-com:vml" fill="true" stroke="false" style="width: 600px; height: 350px;">
            <v:fill type="frame" src="https://dummyimage.com/600x350/d9f0ff/cccccc.jpg" color="#ffffff" />
            <v:textbox inset="0, 0, 0, 0">
            <![endif]-->
            <table class="hero__inner" width="100%" border="0" cellspacing="0" cellpadding="0">
                <tr>
                    <td class="align-center">
                        <h1>Title</h1>
                    </td>
                </tr>
                <tr>
                    <td class="align-center">Content goes here ...</td>
                </tr>
                <tr>
                    <td>
                        <table class="btn btn--blue" border="0" cellpadding="0" cellspacing="0" align="center">
                            <tr>
                                <td>
                                    <a href="#">Click me!</a>
                                </td>
                            </tr>
                        </table><!-- /.btn -->
                    </td>
                </tr>
            </table><!-- /.hero__inner -->
            <!--[if gte mso 9]>
            </v:textbox>
            </v:rect>
            <![endif]-->
        </td><!-- /.hero -->
    </tr>
</table><!-- /.container -->
```
