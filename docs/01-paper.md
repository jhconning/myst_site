---
modified: 2024-06-25T02:22:22.363Z
title: Intro to Myst
keywords: [myst, markdown, jupyter, sphinx, latex]
export: pdf
---

A tutorial to evolve markdown documents and notebooks into structured data.

:::{note}
#TODO:
- [ ] How do I STOP the server
- [ ] How to recreate the PDF
:::

## Things you can do

## Grids

::::{grid} 1 2 2 2

:::{card}
:header: **Instructor Name**

![Instructor Name](images/firefly.jpg)

+++

* **Office Hours**: Tue 11-12pm (Evans 4019)
* **Pronouns**: She/Her
* [instructor@berkeley.edu](mailto:instructor@berkeley.edu)
:::

:::{card}
:header: **GSI Name**

![Instructor Name](images/firefly.jpg)

+++

* **Office Hours**: MW 2-3pm (Evans 3137)
* **Pronouns**: She/Her
* [gsi-name@berkeley.edu](mailto:gsi-name@berkeley.edu)

:::

::::



### Markdown syntax

**Bold** and *italic* and {del}`strikethrough` text. 

Line breaks \\ \
don't matter.

Bullets
- One 
- two

Numbered lists
1. one
2. two


H{sub}`2`O, and 4{sup}`th` of July using `{sub}` and `{sup}`.

{kbd}`Ctrl` + {kbd}`Space`

Well {abbr}`MyST (Markedly Structured Text)` is cool!

## Quotations

> To be or not to be, that is the question.
>
> --- Hamlet

Footnotes 

 Manually-numbered footnote reference[^1]

[^1]: This is a manually-numbered footnote definition.


## Figures and math

:::{figure} ./images/citations.png
:label: citations
:align: right
Citations are rendered with a popup directly inline.
:::

:::{math}
:label: math_one
x^2
:::

This should also work:

$$
F(T,L) = A T^\alpha L^\beta
$$


This math is a role, {math}`e=mc^2`, while this math is wrapped in dollar signs, $Ax=b$.


:::{note}
Many of these instances are mentioned on [the Myst page](https://mystmd.org/guide/quickstart-myst-documents).
:::


See [](#citations) for more information.

.


:::{tip} Click me
:class: dropdown
Try changing `tip` to `warning`!
:::

:::{dropdown} Dropdown
Try changing `tip` to `warning`!
:::


### Tables




:::{table} Table caption
:label: table
:align: center

| foo | bar |
| --- | --- |
| baz | bim |

:::


Python code block:

```python
import matplotlib.pyplot as plt

plt.plot([1, 2, 3], [1, 2, 3], 'go-', label='line 1', linewidth=2)
```


Code block with emphasized lines

```{code} python
:linenos:
:emphasize-lines: 2
import matplotlib.pyplot as plt
plt.plot([1, 2, 3], [1, 2, 3], 'go-', label='line 1', linewidth=2)
```

You can point to files:

```{code} yaml
:filename: myst.yml
project:
  title: Showing Filenames in code-blocks
```

:::{figure} https://github.com/rowanc1/pics/blob/main/mountains.png
:label: fig_mountain
:align: left
Here's a cool figure.
:::


You can use `{embed}` to include earlier labeled content, like this equation:

```{embed} #plasma
:remove-input: true
:remove-output: false
:placeholder: ./image/static.png
<!-- this will be a replacement image -->
```


We can also embed using image syntax `![](#embed)` to always get only the output, rather than the entire notebook cell as above.

![mountain image](#plasma)


.

