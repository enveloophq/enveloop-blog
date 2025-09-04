---
title: Designing Messages in Enveloop
publishDate: 2023-01-17
tags:
  - feature
description: Learn how to design beautiful messages with Enveloop's powerful, but easy-to-use message builder.
lang: en
abbrlink: designing-messages-in-enveloop
---

![Designing Messages in Enveloop Header](/img/header-designing-messages.png)

> Enveloop is a developer-focused message builder and API that makes it easy to design &amp; send beautiful emails and texts from your app using one simple implementation. You can sign up for free at: [https://app.enveloop.com](https://app.enveloop.com).

We've talked about [Enveloop Templates](https://blog.enveloop.com/enveloop-templates/) (or Message Templates) and described how templates act as the top-level containers for all the content you want to include in a message. In this article, we're going to build on this and talk about how you can easily add layout and design to your content.

### Enveloop Message Builder

Enveloop's Message Builder is the heart of our service, allowing developers to effortlessly build out transactional messages that would normally be coded inside your app. You can create both text-only (SMS, MMS) messages as well as messages that support design elements — email for now, but more coming soon!

Instead of having to code HTML &amp; CSS and test for numerous mail clients, Enveloop gives you all this control with a friendly UI and provides you confidence that your messages will display correctly to your end users.

Let's dive into how to create beautiful messages in Enveloop!

### A Quick Reminder

If you're unfamiliar with the structure of message templates, we've [written some articles](https://blog.enveloop.com/enveloop-templates/) and have some [great docs](https://docs.enveloop.com) that offer a more detailed view. As a brief reminder, Enveloop messages are structured this way:

![Flow of structure for an Enveloop Message](/img/designing-messages-enveloop-structure.png)

A **Template** acts as a container for your content. **Sections** represent groups of content and can also have layouts (single vs. multi-column) associated with them, like headers and footers. **Elements** are specific types of content: text, buttons, images, etc.

When you are sending **email** **messages** with Enveloop, each of these message components have styling options you can use. Let's briefly learn about each and its capabilities.

> 💡 If you're just getting started with Enveloop, a great way to see all the design capabilities of Enveloop is to create a template with one of the designs from our template gallery.

### Template Styles

Templates hold all the content of your messages. Think of them as the outer structure of, for example, an email you want to send *(like a "Forgot Password" email)*. 

Templates have style properties. Since they hold the content of your messages, the values any styles you define here (colors, fonts, etc.) can be inherited by the content that you put inside your template. 

A simple illustration: If, in your **Template Style** tab, you set text color to be dark gray, the text of any content you place inside your template, including sections and elements, will automatically inherit that color – unless you define a different color for that content in the Section and Element styles. We'll discuss that in a moment!

You can view and modify template styles by clicking the outside of the message and choosing the "Template Styles" tab.

![Template Styles](/img/designing-messages-template-style.png)

*Enveloop Templates represent any message you may send. They can also hold global styles for your message, like background color and padding.*

### Section Styles

Any content you want to add to a template will be contained in a section. Sections have styles, too. When you click on a section in the message, you have a couple of options: **Layout** and **Section Style**.

Section styles, like template styles, allow you to control colors, fonts, and padding.

![Section Styles](/img/designing-messages-section-style.png)

*Click on a Section in your message and you can alter the layout and design using the tabs in the right-hand drawer.*

### Element Styles

Along with the content that you can place in sections, you can include additional Elements that are useful in crafting messages. These include:

- Text
- Image
- Button
- Heading
- Divider

Each of these elements has style options as well -- according to its use. A button, for example, includes colors, sizing, and structure (rounded, square, etc.)

![Element Styles](/img/designing-messages-element-style.png)
*Elements have unique design properties, giving you numerous ways to customize messages with Enveloop.*

### How it All Connects

Understanding the hierarchy of **elements** *(inside of)* **sections** *(inside of)* **templates** allows you to understand how each type inherits from the other. This provides you both the level of specificity that you need as well as more powerful global control of the design of your message.

### Markdown, too!

One final note: Along with the UI that Enveloop provides to you to control your design, don't forget about the use of Markdown for added formatting of text. This includes support for headings, paragraphs, links, emphasis, blockquotes, lists, etc. We discuss this in greater detail in [Enveloop Docs for Markdown](https://docs.enveloop.com/product-guides/markdown-for-formatting).

### Try it Out!

Enveloop is [**free to get started**](https://app.enveloop.com) and you can build out and send you first template in under 5 minutes! Storing all your message code, design, and provider integrations in your app is an anti-pattern. Enveloop helps you send better messages and allows you to easily delegate messaging to others on your team!

Happy Sending! 🚀
