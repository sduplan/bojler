---
layout:                     default

title:                      Getting started
description:                In this section you'll find features and support table, basic information about Bojler and how to use it properly. If you're first time user then you should read this first.
keywords:                   boilerplate, grid, email css, email, email boilerplate, email campaigns, email template, bojler, slicejack

page_nav:                   true
page_nav_prev:              false
page_nav_prev_content:
page_nav_prev_url:
page_nav_next:              true
page_nav_next_content:      Typography
page_nav_next_url:          /typography
---

## Introduction
Bojler is an email boilerplate and a guideline for writing HTML code that will render correctly across each of the most popular email clients.

If you have experience with email template development, you know how painful it is to build a perfect email template that works across all email clients.

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
            <td>Premade blocks of code ready to use on your custom email template.</td>
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
