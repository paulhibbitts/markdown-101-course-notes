# Code and Tables

## Inline Code

Wrap inline snippets of code with a single backtick: `` `<section></section>` ``.

## Block Code

Use triple backticks to fence a whole block of code, optionally naming a language right after the first fence for syntax highlighting:

<pre>
```java
public class Course {
  public static void main(String[] args) {
    System.out.println("Welcome to the course!");
  }
}
```
</pre>

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

---

Next: [Links and Images](04-links-and-images.md)
