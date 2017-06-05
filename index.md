---
layout:                     default

title:                      bojler
description:                Bojler is merely a guideline for writing HTML code
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
Bojler is merely a guideline for writing HTML code that will render correctly across each of the most popular email clients.

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
            <td>Bojler defaults to the system font of a particular operating system.</td>
        </tr>
        <tr>
            <td>Grid</td>
            <td>Bojler uses 12-column grid with a 600px container.</td>
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
First of all we suggest you to use `email-lite.html` or `email-grid-lite.html` for your email development because you should **avoid using comments** in your final email campaign. Else you may get blocked by SPAM filters.

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
Best way to send your HTML email would be using an Email Service Provider (ESP) such as [MailChimp](http://www.mailchimp.com) or [Campaign Monitor](https://www.campaignmonitor.com/). If you’re just running a quick test we recommend you to use [https://putsmail.com/](https://putsmail.com/)

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
Bojler defaults to the system font of a particular operating system. This method can boost performance because the browser or e-mail client doesn't have to download any font files, it's using one it already had.

The beauty of system fonts is that it matches what the current OS uses, so it can be a comfortable look.

```css
html,
body,
table,
table td {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
}
```

## Grid system
Bojler uses 12-column grid with a 600px container. <br>On mobile devices (under 600px wide), columns become full width and stack vertically.

### Use grid version of boilerplate
We have created special `email-grid.html` file for email development with our grid. Basically it's a `email-lite.html` combined with grid CSS.

### Media queries
We suggest you to use this media query when building responsive email with our grid.

```css
@media screen and (max-width: 600px) {}
```

### Grid options
See how aspects of this grid work across devices with a handy table.
<table>
    <thead>
        <tr>
            <th></th>
            <th>Small devices (&lt;600px)</th>
            <th>Large devices (&gt;600px)</th>
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

**Example:**
```html
<table class="container" border="0" cellpadding="0" cellspacing="0">
    <tr>
        <td></td>
    </tr>
</table><!-- /.container -->
```

### Columns
Content should be placed within columns, and columns should be placed as `<td>` of your `.container`.
You can define width of the column with classes such as `.column-1`, `.column-2`, `.column-3` etc.
In `.container` you can place max. 12 columns.

**Examples:**
```html
<table class="container" border="0" cellpadding="0" cellspacing="0">
    <tr>
        <td class="column-12 first last">
            <table border="0" cellpadding="0" cellspacing="0">
                <tr>
                    <td>Content goes here</td>
                </tr>
            </table>
        </td><!-- /.col -->
    </tr>
</table><!-- /.container -->
```

```html
<table class="container" border="0" cellpadding="0" cellspacing="0">
    <tr>
        <td class="column-6 first">
            <table border="0" cellpadding="0" cellspacing="0">
                <tr>
                    <td>Content goes here</td>
                </tr>
            </table>
        </td><!-- /.col -->

        <td class="column-6 last">
            <table border="0" cellpadding="0" cellspacing="0">
                <tr>
                    <td>Content goes here</td>
                </tr>
            </table>
        </td><!-- /.col -->
    </tr>
</table><!-- /.container -->
```

```html
<table class="container" border="0" cellpadding="0" cellspacing="0">
    <tr>
        <td class="column-3 first">
            <table border="0" cellpadding="0" cellspacing="0">
                <tr>
                    <td>Content goes here</td>
                </tr>
            </table>
        </td><!-- /.col -->

        <td class="column-3">
            <table border="0" cellpadding="0" cellspacing="0">
                <tr>
                    <td>Content goes here</td>
                </tr>
            </table>
        </td><!-- /.col -->

        <td class="column-3">
            <table border="0" cellpadding="0" cellspacing="0">
                <tr>
                    <td>Content goes here</td>
                </tr>
            </table>
        </td><!-- /.col -->

        <td class="column-3 last">
            <table border="0" cellpadding="0" cellspacing="0">
                <tr>
                    <td>Content goes here</td>
                </tr>
            </table>
        </td><!-- /.col -->
    </tr>
</table><!-- /.container -->
```

### First and last classes

The `.first` class adds the appropriate amount of padding-left to space the content away from the container’s edge. The `.last` class is added to your last set of columns in a row to add padding-right to the column. If you have columns in between `.first` and `.last`, these classes are not needed on the middle columns.

The reason these classes exist is that CSS properties like `:last-child` don’t work in most email clients so a class is needed.

**Example:**
```html
<table class="container" border="0" cellpadding="0" cellspacing="0">
    <tr>
        <td class="column-4 first">
            <table border="0" cellpadding="0" cellspacing="0">
                <tr>
                    <td>Content goes here</td>
                </tr>
            </table>
        </td><!-- /.col -->

        <td class="column-4">
            <table border="0" cellpadding="0" cellspacing="0">
                <tr>
                    <td>Content goes here</td>
                </tr>
            </table>
        </td><!-- /.col -->

        <td class="column-4 last">
            <table border="0" cellpadding="0" cellspacing="0">
                <tr>
                    <td>Content goes here</td>
                </tr>
            </table>
        </td><!-- /.col -->
    </tr>
</table><!-- /.container -->
```

### Columns without gutter

If you need columns without gutter than you should use `.no-gutter` class on your `.container`.

**Example:**
```html
<table class="container no-gutter" border="0" cellpadding="0" cellspacing="0">
    <tr>
        <td class="column-6">
            <table border="0" cellpadding="0" cellspacing="0">
                <tr>
                    <td>Content goes here</td>
                </tr>
            </table>
        </td><!-- /.col -->

        <td class="column-6">
            <table border="0" cellpadding="0" cellspacing="0">
                <tr>
                    <td>Content goes here</td>
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

Preheader is already included to all boilerplate files, if you don't need it just erase it.

**Example:**
```html
<table id="preheader">
    <tr>
        <td>Your preheader text goes here. This block should be hidden.</td>
    </tr>
</table><!-- /#preheader -->
```
