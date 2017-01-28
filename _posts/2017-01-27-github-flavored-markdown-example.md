---
layout: post
title: Github Flavored Markdown Example
date: 2017-01-28 13:05:00
disqus: y
---

# Syntax guide

## Emphasis

*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_

## Lists

### Unordered

* Item 1
* Item 2
  * Item 2a
  * Item 2b

### Ordered

1. Item 1
2. Item 2
3. Item 3
   * Item 3a
   * Item 3b

### Images

![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)

## Links

http://github.com - automatic!
[GitHub](http://github.com)

## Blockquotes

As Kanye West said:

> We're living the future so
> the present is our past.

## Inline code

I think you should use an
`<addr>` element here instead.

# GitHub Flavored Markdown

## Syntax highlighting

Here’s an example of how you can use syntax highlighting with GitHub Flavored Markdown:

```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

You can also simply indent your code by four spaces:

    function fancyAlert(arg) {
      if(arg) {
        $.facebox({div:'#foo'})
      }
    }

Here’s an example of Python code without syntax highlighting:

```
def foo():
    if not bar:
        return True
```

## Task Lists

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

## Tables

You can create tables by assembling a list of words and dividing them with hyphens - (for the first row), and then separating each column with a pipe |:

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column
