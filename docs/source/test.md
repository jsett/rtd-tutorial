# hello world

```py
import time
for x in range(0,100):
    print(f"hello {x}")
    time.sleep(1)
```

```
.. toctree::

   usage
   test
   api
```

```{code-block} python
:lineno-start: 10
:emphasize-lines: 1, 3

a = 2
print('my 1st line')
print(f'my {a}nd line')
```

:::{admonition} Here's my title
:class: tip

Here's my admonition content.{sup}`1`
:::

(header-label)=
# A header

[My reference](#header-label)

# what is this

dont know what is is.

# first

```{mermaid}
flowchart LR
  A[Jupyter Notebook] --> C
  B[MyST Markdown] --> C
  C(mystmd) --> D{AST}
  D <--> E[LaTeX]
  E --> F[PDF]
  D --> G[Word]
  D --> H[React]
  D --> I[HTML]
  D <--> J[JATS]
```

# second 

```mermaid
flowchart LR
  A[Jupyter Notebook] --> C
  B[MyST Markdown] --> C
  C(mystmd) --> D{AST}
  D <--> E[LaTeX]
  E --> F[PDF]
  D --> G[Word]
  D --> H[React]
  D --> I[HTML]
  D <--> J[JATS]
```