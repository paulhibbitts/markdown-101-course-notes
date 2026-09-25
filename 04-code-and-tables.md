# Code and Tables

## Inline Code

Wrap inline snippets of code with a single backtick: `` `<section></section>` ``.

## Indented Code

You can also indent several lines of code by at least four spaces:

<pre>
  // Some comments
  line 1 of code
  line 2 of code
</pre>

Renders to:

    // Some comments
    line 1 of code
    line 2 of code

This works, but fenced code blocks (below) are usually easier to read and write, since they don't depend on exact indentation.

## Block Code

Use triple backticks to fence a whole block of code, optionally naming a language right after the first fence for syntax highlighting:

````markdown
```java
public class Course {
  public static void main(String[] args) {
    System.out.println("Welcome to the course!");
  }
}
```
````

Renders to:

```java
public class Course {
  public static void main(String[] args) {
    System.out.println("Welcome to the course!");
  }
}
```

## Tables

Tables are created with pipes between cells and a row of dashes beneath the header. The pipes don't need to line up visually.

```markdown
| Assignment | Weight |
| ---------- | ------ |
| Homework 1 | 10%    |
| Midterm    | 30%    |
| Final Project | 40% |
```

Renders to:

| Assignment | Weight |
| ---------- | ------ |
| Homework 1 | 10%    |
| Midterm    | 30%    |
| Final Project | 40% |

### Right-Aligned Columns

Adding a colon on the right side of a column's dashes right-aligns that column:

```markdown
| Assignment | Weight |
| ---------- | -----: |
| Homework 1 |    10% |
| Midterm    |    30% |
```

Renders to:

| Assignment | Weight |
| ---------- | -----: |
| Homework 1 |    10% |
| Midterm    |    30% |

---

Next: [Links and Images](05-links-and-images.md)
