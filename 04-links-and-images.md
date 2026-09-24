# Links and Images

## A Basic Link

```markdown
[Markdown Guide](https://www.markdownguide.org)
```

Renders to: [Markdown Guide](https://www.markdownguide.org)

## Adding a Title

A title adds a tooltip that appears on hover:

```markdown
[Markdown Guide](https://www.markdownguide.org "Visit the Markdown Guide")
```

Renders to (hover over the link to see the tooltip): [Markdown Guide](https://www.markdownguide.org "Visit the Markdown Guide")

## Named Anchors

Named anchors let you jump to a specific point on the same page &ndash; handy for a table of contents at the top of a long file. Add an `id` to a heading (or any element):

```markdown
## Week 1 <a id="week-1"></a>
Content for week one.

## Week 2 <a id="week-2"></a>
Content for week two.
```

Then link to it from anywhere on the page:

```markdown
Jump straight to [Week 2](#week-2).
```

## Images

Images have a similar syntax to links but include a preceding exclamation point.

```markdown
![Image of Minion](https://octodex.github.com/images/minion.png)
```

![Image of Minion](https://octodex.github.com/images/minion.png)

and using a local image (which also displays on GitHub):

```markdown
![Image of Octocat](images/octocat.png)
```

![Image of Octocat](images/octocat.png)

---

Next: [Blockquotes and Extras](05-blockquotes-and-extras.md)
