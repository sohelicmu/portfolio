---
layout: default
title:  Markdown
nav_order: 2
---
# Markdown: What is it?

Markdown is a very simple text-encoding system, or markup language, for formatting plain text. You may have seen it or used it in discussion forums like Reddit to style text in certain ways – like in **bold** or *italics* or ***both***. It's also often used in GitHub for assembling nicely looking README files, and it's used for the content that makes up this site. GitHub Pages (and Jekyll) reads Markdown files (usually with the file extension `.md` or `.markdown`) and converts them to valid HTML.

If you prefer writing in HTML, you can do that too. You can also combine HTML with your Markdown to add things like `<iframe>` and custom scripts in the same Markdown document.
{: .note}

Markdown syntax is fairly straightforward and somewhat easy to remember. It uses common characters like asterisks, dashes, and the hashtag symbol mixed with spaces to stylize text. For instance text surrounded by two asterisks makes the text italicized.

`*Hello!*` = *Hello!*

We can also make the text bold.

`**Hello**` = **Hello**

This is just scraping the surface of what can be done with Markdown, as you can see from GitHub user [obebm503](https://github.com/obedm503)'s [Markdown Kitchen Sink](https://github.com/obedm503/markdown-kitchen-sink). For those of you who use HTML, you can think of Markdown as a super simplified version of that – you can add images, links, tables, quotes, and other things with very simple markdown syntax.

Let's try out an online editor to practice a couple of common Markdown markups.

### *1* Go to [markdownlivepreview.com](https://markdownlivepreview.com/){:target="_blank"}

Clicking on the Markdown editor link will take you to web page with document displayed in two windows. On the left is the plain text Markdown, and on the right is the styled version rendered online. You can edit the text on the left, and changes will appear on the right.

### *2* Change the title of the document

The first line of this document is a [heading](https://www.w3.org/WAI/tutorials/page-structure/headings/) – H1 to be specific. How do I know this? Because there is 1 "number sign" and a space before the rest of the text. Any line of text after a `# ` will be rendered as H1.

On the left, change `# Markdown syntax guide` to `# [your name]'s new document`

### *3* Add a link

Adding links to your documents is very easy. All you need is your preferred link text and the URL. The Markdown syntax is:
`[your preferred text](the URL)`

Add this link to the CMU Libraries Robotics Project Digital Exhibit somewhere in the document:

`[Robotics Project Digital Exhibit](https://exhibits.library.cmu.edu/roboticsproject/)`
