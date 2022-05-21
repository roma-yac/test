# PyMdown Extensions

[TOC]

## [BetterEm](https://facelessuser.github.io/pymdown-extensions/extensions/betterem/)

* Won't highlight *

*Will highlight*

***I'm italic and bold* I am just bold.**

***I'm bold and italic!** I am just italic.*

___A lot of underscores____________is okay___

___A lot of underscores____________is okay___

__This will all be bold __because of the placement of the center underscores.__

__This will all be bold __ because of the placement of the center underscores.__

__This will NOT all be bold__ because of the placement of the center underscores.__

__This will all be bold_ because of the token is less than that of the surrounding.__

*All will * be italic*

*All will *be italic*

*All will not* be italic*

*All will not ** be italic*

**All will * be bold**

**All will *be bold**

**All will not*** be bold**

**All will not *** be bold**

## [SuperFences](https://facelessuser.github.io/pymdown-extensions/extensions/superfences/)

> ```
  a fenced block
  ```

- 
    ```
    a fenced block
    ```

Definition
: 
    ```
    a fenced block
    ```
    
## [Arithmatex](https://facelessuser.github.io/pymdown-extensions/extensions/arithmatex/)

$p(x|y) = \frac{p(y|x)p(x)}{p(y)}$, \(p(x|y) = \frac{p(y|x)p(x)}{p(y)}\).

$$
E(\mathbf{v}, \mathbf{h}) = -\sum_{i,j}w_{ij}v_i h_j - \sum_i b_i v_i - \sum_j c_j h_j
$$

\[3 < 4\]

\begin{align}
    p(v_i=1|\mathbf{h}) & = \sigma\left(\sum_j w_{ij}h_j + b_i\right) \\
    p(h_j=1|\mathbf{v}) & = \sigma\left(\sum_i w_{ij}v_i + c_j\right)
\end{align}

## [Caret](https://facelessuser.github.io/pymdown-extensions/extensions/caret/)

^^Insert me^^

H^2^0, text^a\ superscript^

## [Details](https://facelessuser.github.io/pymdown-extensions/extensions/details/)

???+ note "Open styled details"

    ??? danger "Nested details!"
        And more content again.

??? success
    Content.

??? warning classes
    Content.

## [Emoji](https://facelessuser.github.io/pymdown-extensions/extensions/emoji/)

:smile: :heart: :thumbsup:

## [SuperFences](https://facelessuser.github.io/pymdown-extensions/extensions/superfences/)

> ```
  a fenced block
  ```

- 
    ```
    a fenced block
    ```

Definition
: 
    ```
    a fenced block
    ```

```{.python .extra-class linenums="1"}
import hello_world
print(hello_world())
```

``` {linenums="1 1 2"}
"""Some file."""
import foo.bar
import boo.baz
import foo.bar.baz
```

```{.py3 hl_lines="1 3" linenums="2"}
"""Some file."""
import foo.bar
import boo.baz
import foo.bar.baz
```

```{.py3 hl_lines="1-2 5 7-8"}
import foo
import boo.baz
import foo.bar.baz

class Foo:
   def __init__(self):
       self.foo = None
       self.bar = None
       self.baz = None
```

```{.py3 title="My Cool Header"}
import foo.bar
import boo.baz
import foo.bar.baz
```

```{.py3 title="hello.py" linenums="1"}
import foo.bar
import boo.baz
import foo.bar.baz
```

## [InlineHilite](https://facelessuser.github.io/pymdown-extensions/extensions/inlinehilite/)

Here is some code: `#!py3 import pymdownx; pymdownx.__version__` or `:::css border: 0px;`.

The mock shebang will be treated like text here: ` #!js var test = 0; `.

## [Keys](https://facelessuser.github.io/pymdown-extensions/extensions/keys/)

++ctrl+alt+delete++

## [Mark](https://facelessuser.github.io/pymdown-extensions/extensions/mark/)

==mark me==

==smart==mark==

## [SmartSymbols](https://facelessuser.github.io/pymdown-extensions/extensions/smartsymbols/)

(tm) --> <-- <--> =/= c/o

## [Tabbed](https://facelessuser.github.io/pymdown-extensions/extensions/tabbed/)

=== "Tab 1"
    Markdown **content**.

    Multiple paragraphs.

=== "Tab 2"
    More Markdown **content**.

    - list item a
    - list item b

===! "Tab A"
    Different tab set.

=== "Tab B"
    ```
    More content.
    ```
    
=== "New Tab"
    > Great cite

## [Tasklist](https://facelessuser.github.io/pymdown-extensions/extensions/tasklist/)

Task List

- [X] item 1
    * [X] item A
    * [ ] item B
        more text
        + [x] item a
        + [ ] item b
        + [x] item c
    * [X] item C
- [ ] item 2
- [ ] item 3

## [Tilde](https://facelessuser.github.io/pymdown-extensions/extensions/tilde/)

~~Delete me~~

CH~3~CH~2~OH

text~a\ subscript~