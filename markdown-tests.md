# Markdown tests { #top }

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
```

``` { .python .foo #example }
print('Hello')
```

``` { .lang linenos=true linenostart=42 hl_lines="43-44 50" title="An Example Code Block" }
A truncated code block...
```