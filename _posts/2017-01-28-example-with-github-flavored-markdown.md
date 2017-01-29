---
layout: post
title: Example with GitHub Flavored Markdown
comment: y
---

---

## Syntax guide

### Emphasis

*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_

### Lists

#### Unordered

* Item 1
* Item 2
  * Item 2a
  * Item 2b

#### Ordered

1. Item 1
2. Item 2
3. Item 3
   * Item 3a
   * Item 3b

#### Images

![scribble-enhanced logo](/images/scribble.png)

### Links

[GitHub](http://github.com)

### Blockquotes

As Kanye West said:

> We're living the future so
> the present is our past.

### Inline code

I think you should use an
`<addr>` element here instead.

---

## GitHub Flavored Markdown

### Syntax highlighting

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
