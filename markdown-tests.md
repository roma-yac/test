---
Title:   My Document1
Summary: A brief description of my document.
Authors: Waylan Limberg
         John Doe
Date:    October 2, 2007
blank-value:
base_url: http://example.com
---

# Markdown tests { #top }

[TOC]

## Зміст (TOC)

### `markdown.markdown(text [, **kwargs])` { #markdown data-toc-label='markdown.markdown' }

#### Заголовок 4 рівня

## SmartyPants

'single quotes'
"double quotes"
<<angled quotes>>
12 `<<` 45
... -- ---

## Sane Lists

1. Ordered item 1
2. Ordered item 2

* Unordered item 1
* Unordered item 2

A Paragraph.
* Not a list item.

4. Apples
5. Oranges
6. Pears

## Syntax highlighting

```python
print(2+2)
```

```
text output
```

## Admonition

!!! type "optional explicit title within double quotes"
    Any number of other indented markdown elements.

    This is the second paragraph.

!!! note
    You should note that the title will be automatically capitalized.

!!! danger "Don't try this at home"
    ...
    
!!! important ""
    This is an admonition box without a title.

!!! danger highlight blink "Don't try this at home"
    ...

## Tables

First Header  | Second Header
------------- | ------------:
Content Cell  | Content Cell
Content Cell  | Content Cell

## Footnotes

Footnotes[^1] have a label[^@#$%] and the footnote's content.

[^1]:
    The first paragraph of the definition.

    Paragraph two of the definition.

    > A blockquote with
    > multiple lines.

        a code block

    A final paragraph.

[^@#$%]: A footnote on the label: "@#$%".

## Abbreviations

The HTML specification
is maintained by the W3C.

*[HTML]: Hyper Text Markup Language
*[W3C]:  World Wide Web Consortium

## Attribute Lists

This is a paragraph.
{: #someid .someclass somekey='some value' }

### A hash style header {: #hash }

[link](#top){: class="foo bar" title="Some title!" }

| set on td    | set on em   |
|--------------|-------------|
| *a* { .foo } | *b*{ .foo } |

## Definition Lists

Apple
:   Pomaceous fruit of plants of the genus Malus in
    the family Rosaceae.

Orange
:   The fruit of an evergreen tree of the genus Citrus.

## Fenced Code Blocks

A paragraph before the code block.

```
a one-line code block
```

A paragraph after the code block.

~~~
a one-line code block
~~~

````
```
````

```

a three-line code block

```

* A list item.
```
not part of the list
```

``` python
print(2+2)
def func(a, b):
    return a + b
```

``` { .python .foo #example }
print('Hello')
```

``` { .lang linenos=true linenostart=42 hl_lines="43-44 50" title="An Example Code Block" }
A truncated code block...
```