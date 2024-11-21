---
runme:
  id: 01JD663JGTPE6RGP1ESYH62XWW
  version: v3
---

## Mermaid diagrams

A great way to quickly demonstrate concepts visually, simply install [this VS Code extension](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-mermaid) for Markdown Preview Mermaid Support.

**Put the following in a Markdown block in the Notebook:**

<pre>
::: mermaid
graph TD;
A-->B;
A-->C;
B-->D;
C-->D;
:::

**And it will render the diagram:**

::: mermaid
graph TD;
A-->B;
A-->C;
B-->D;
C-->D;
:::
