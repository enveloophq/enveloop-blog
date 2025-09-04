---
title: Enveloop Templates
publishDate: 2023-01-10
tags:
  - Feature
  - Product
description: Enveloop Templates allow developers to easily create, style, and connect messages to send from their app to their users.
lang: en
abbrlink: enveloop-templates
---

![Enveloop Templates Header](/img/header-templates.png)

> Enveloop is a developer-focused message builder and API that makes it easy to design &amp; send beautiful emails and texts from your app using one simple implementation. You can sign up for free at: [https://app.enveloop.com](https://app.enveloop.com).

Ok, so let's talk templates. A bit of a boring word, but it's the powerful core of Enveloop. Templates (or Message Templates) are the top-level containers for your **content**, **design**, and **dynamic content.** Each template represents a type of message you need to send.

For example:

- User Invited
- User Welcome
- Forgot Password
- New Team Created

Templates are the building blocks of the transactional message platform you can create on top of Enveloop. You can add as many as you need. Templates give you a lot of power &amp; control and, in our coming blog posts, we'll talk more about how to take advantage.

In this article, we'll cover the basics of what a template is. The easiest way to do this in Enveloop is to use one of the options from our **Template Gallery**. Select a style, color, and name of your template and you're ready to go. *You can also start with a blank template.*

![Template Gallery](/img/template-template-gallery.png)

### Template Modes

After creating a new template, you'll enter into the **Build** mode.

![Build Mode](/img/template-build-mode.png)

*At the top of the template builder, you can determine the template mode you are in.*

#### Build Mode

When working with Enveloop templates, this is where you'll spend most of your time and where you can edit your content and design. Click on different parts of the message to start editing. Also, in the right drawer, styling options are available for fonts, colors, spacing, and layout.

#### Test Mode

After creating a template, switching to **Test** mode allows you to see an in-browser preview of your message. Also, you can quickly send an actual test message to your inbox to preview your message in your personal inbox / mail client.

Also important to note, in this mode, the right drawer in the UI has become a place to enter test data for any variables you included in your message template. This is a great way to preview how dynamic content, from your app, will render in your messages.

Want to see how your message looks in mobile? Enveloop makes this easy with the view window selector located at the bottom of the screen.

![Test Mode](/img/template-test-mode.png)

*View your message in desktop, tablet, and mobile dimensions.*

#### Deploy Mode

Once you are satisfied with your message, **Deploy** mode provides you with language-specific code to embed the necessary API call in your app. You can also cURL a message from a local terminal window.

![Deploy Mode](/img/template-deploy-mode.png)

*Enveloop includes all the detail you need in your API call, including variables.*

### Still More to Cover!

There's plenty of additional detail to cover about message templates – We'll do this in future articles – including: elements, sections, and saved sections.
