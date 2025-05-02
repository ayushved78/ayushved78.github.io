+++
date = '2025-05-02T19:00:16+05:30'
draft = true
title = 'Learn markdown'
showToc = true
tocOpen = true  # optional, opens ToC by default
+++

# Learn Markdown

A complete guide to Markdown syntax, perfect for Hugo + PaperMod users.

## Headings

Use `#` symbols at the start of a line to create headings.

# H1 – Main Title  
## H2 – Section  
### H3 – Subsection  
#### H4 – Smaller Heading

## Text Formatting

**Bold text**  
*Italic text*  
~~Strikethrough~~  
**_Bold and italic_**

You can also use underscores instead of asterisks:

__Bold__  
_Italic_

## Paragraphs and Line Breaks

Separate paragraphs with a blank line.

This is the first paragraph.

This is the second paragraph.

To insert a line break without a new paragraph, end a line with two spaces.  
Like this.  
And this.

## Lists

### Unordered List

- Item 1
- Item 2
  - Subitem A
  - Subitem B

### Ordered List

1. First item
2. Second item
   1. Sub-item 1
   2. Sub-item 2

## Links

[Google](https://www.google.com)  
[Send me an email](mailto:test@example.com)

## Images

![Example image](https://via.placeholder.com/300x150.png)

Or make it clickable:

[![Image](https://via.placeholder.com/150)](https://google.com)

## Code

### Inline Code

Use backticks to wrap code like this: `console.log('Hello World')`

### Code Block

```python
def greet(name):
    print(f"Hello, {name}!")
