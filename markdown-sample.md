---
layout: article
title: Markdown Sample
permalink: markdown-sample.html
key: page-sidebar-aside
cover: /docs/assets/images/axure/page-sidebar-aside.jpg
aside:
  toc: true
sidebar:
  nav: docs-en
---

This is a sample of the kind of work I can do using markdown. I wrote it as a brief tutorial on how to use markdown aimed at beginner **technical writers**.

# Headings

Headings and their hierarchy are established using #

So, the way to create different sizes of titles and subtitles, like this:

![Titles example](/assets/images/using-markdown/image-1.png){:.border.shadow}

Is to type them in this way, using #:

```
# Title 1
## Title 2
### Title 3
```

You can use this to create an information hierarchy in your documents, and to make the tables of contents of your online documentation easier to navigate.

&nbsp;

# Text Style

&nbsp;

## Bold Text

For **bold text**, write this:

```
**example text**
```

&nbsp;

## Italic Text

For *italic text*, write this:

```
*example text*
```

&nbsp;

## Bold & Italic Text

For ***bold & italic text***, write this:

```
***example text***
```

&nbsp;

## Underlined Text

For <ins>underlined text</ins> we can use GitHub markdown, like this:

```
<ins>example text</ins>
```

&nbsp;

## Strikethrough Text

For ~~strikethroughs~~, write this:

```
~~example text~~
```

# Lists

You can create **ordered** and **unordered** lists in markdown.

&nbsp;

## Ordered Lists

For **ordered** lists like this:

1. First
2. Second
3. Third

Write this:

```
1. First
2. Second
3. Third
```

Note that if you write something like this with random numbers

```
1. First
27. Second
8. Third
```

Markdown will still make it look like this:

1. First
2. Second
3. Third

&nbsp;

## Unordered Lists

For **unordered** lists like this:

* First
* Second
* Third

Write this:

```
* First
* Second
* Third
```

or this:

```
- First
- Second
- Third
```

&nbsp;

# Code

To write `inline code`, write this:

```
`example text`
```

To write a code block, write this:

![codeblock](/assets/images/using-markdown/img-code-01.png){:.border.shadow}

The text will display "boxed", like this:

```
this is an example
```

You can also add syntax highlighting to the code:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

By writing this:

![codeblock with highlights](/assets/images/using-markdown/img-code-03.png){:.border.shadow}

You can also add line numbers to the code:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

By writing this:

![codeblock with line numbers](/assets/images/using-markdown/img-code-02.png){:.border.shadow}

&nbsp;

# Horizontal Rule

To add a horizontal rule like this:

---

You must write this:

```
---
```

&nbsp;

# Links

To add a link, use the following:

```
[link title](https://www.examplelink.com)
```

&nbsp;

# Images

To add an image, use the following:

```
![alt text](image.jpg)
```

&nbsp;

# Line Spacing

In markdown a regular empty line space is achieved by leaving an empty line in between paragraphs. So, this:

text

text

text

is written like this:

```
text

text

text
```

If you do this, leaving no empty lines in between:

```
text
text
text
```

This will be the result:

text text text

Also, Markdown will ignore double spacesbetween lines. So, if you write this:

```
text


text


text
```

You will still get a single empty line in between:

text


text


text

&nbsp;

# Tables

For a table like this:

| Title | Title |
| --- | --- |
| Text | Text |
| Text | Text | 

Use this format:

```
| Title | Title |
| --- | --- |
| Text | Text |
| Text | Text | 
```

&nbsp;

# Tasks List

For a tasks list like this:

- [x] Task 1
- [ ] Task 2
- [ ] Task 3 

User this format:

```
- [x] Task 1
- [ ] Task 2
- [ ] Task 3 
```

Consider that `[x]` will show the task as selected, while `[ ]` will show the task as unselected.

&nbsp;
