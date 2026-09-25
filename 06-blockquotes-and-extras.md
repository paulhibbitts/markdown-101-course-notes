# Blockquotes and Extras

A few more building blocks worth knowing, even if you'll use them less often than headings or lists.

## Blockquotes

For quoting a block of content from another source, add `>` before each line you want to quote:

```markdown
> **Fusion Drive** combines a hard drive with flash storage (a solid-state drive) and presents it as a single logical volume with the space of both drives combined.
```

Renders to:

> **Fusion Drive** combines a hard drive with flash storage (a solid-state drive) and presents it as a single logical volume with the space of both drives combined.

Blockquotes can also be nested, using `>>` for the inner quote:

```markdown
> Outer quote, first line.
> Outer quote, second line.
>> Inner, nested quote.
```

Renders to:

> Outer quote, first line.
> Outer quote, second line.
>> Inner, nested quote.

## Horizontal Rules

A horizontal rule creates a visual break between sections. Any of the following, on their own line, will produce one:

```markdown
___
---
***
```

Renders to:

___

## Comments

Comments are written using standard HTML comment syntax and never appear in the rendered page &ndash; handy for leaving a note to your future self, or a co-author:

```markdown
<!--
This won't show up in the rendered page.
-->
```

---

Next: [LaTeX and Mermaid](07-latex-and-mermaid.md)
