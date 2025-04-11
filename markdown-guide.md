# The Ultimate Beginner's Guide to Markdown
This guide will walk you through the basic syntax of Markdown. It’s useful for writing documentation, README files, or notes in plain text that render beautifully on platforms like GitHub.

## Headings
You can create different sized headings by using one to six hash (`#`) symbols followed by a space and your heading text. 
The more hash symbols, the smaller the header:
# Heading 1
## Heading 2
### Heading 3
#### Heading 4

```markdown
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
```

## Paragraphs
If you want to create a new paragraph,

make sure there's an extra empty line between the two paragraphs.

```markdown
If you want to create a new paragraph,

make sure there's an extra empty line between the two paragraphs.
```

## Horizontal Line
Use three dashes, `---`, to draw a horizontal line like:

---

## Lists
You can create a bulleted list by using one asterisk, `*` ,followed by a space:
* Bullet 1
* Bullet 2
* Bullet 3

If you want an ordered list, use numbers:
1. First
2. Second
3. Third

### Nested lists
To create a nested list, you indent and then add an asterisk or number followed by a space.

Here's an example of a nested unordered list:
* Bullet 1
  * Sub-bullet 1
  * Sub-bullet 2
* Bullet 2

Here's an example of a nested ordered list:
1. First
   1. First indent
   2. Second indent
2. Second

### Mixed lists
You can also have an ordered list with a nested unordered list like this:
1. First
   * Bullet 1
   * Bullet 2
2. Second

Or vice versa, an unordered list with a nested ordered list like this:
* Bullet 1
  1. First item
  2. Second item
* Bullet 2

## Emphasis
If you wrap your text with the following characters, you can add different types of emphasis:

*Italics* and **Bold** and ***Bold and Italics***
```markdown
*Italics* and **Bold** and ***Bold and Italics***
```

~~Strikethrough~~ and <u>underline</u>
```markdown
~~Strikethrough~~ and <u>underline</u>
```

A <sup>superscript</sup> and a <sub>subscript</sub>
```markdown
A <sup>superscript</sup> and a <sub>subscript</sub>
```

## LaTeX
You can add LaTeX equations two ways:

Inline like $C_6H_12O_6$
```markdown
Inline like $C_6H_12O_6$
```

Or displayed on its own line: $$Area = {\pi}r^2$$
```markdown
Or displayed on its own line: $$Area = {\pi}r^2$$
```

[Click here](https://ashki23.github.io/markdown-latex.html#mathematical-formula) for a quick reference on the most common LaTeX syntax.

## Code Blocks
You can add inline code by adding a set of backticks `inline code`.
To create a code block, enclose the code with a set of three backticks. 
Make sure that you specify the language (e.g., `python`, `bash`, `html`) right after the first three:

```python
# Example of Python code
def greet():
    print("Hello, Markdown!")
```

## Blockquote
To create a blockquote, you start each line with a `>`:

> If your blockquote has multiple paragraphs,
> 
> make sure you have any extra line with just '>' between the paragraphs.

## Links
If you want to show the full URL as a clickable link, just paste it directly:

https://www.google.com

But if you want to hyperlink text:
1. Add the text you want to be shown inside a set of brackets  [Link text]
2. Add the url inside a set of parentheses (link)

Example: [Google](https://www.google.com).

```markdown
Example: [Google](https://www.google.com).
```

## Images
To embed an image:
1. Add an exclamation point (!)
2. Add the text representing the image inside a set of brackets  [Alternative text]
3. Add the url to the link inside a set of parentheses (url for image)

Here's an example of the Markdown logo:

![Markdown logo](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR7F0ge8MNuv4S2WaFiwgs-6fQVN5FGWorjJg&s)

```markdown
![Markdown logo](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR7F0ge8MNuv4S2WaFiwgs-6fQVN5FGWorjJg&s)
```

## Tables
To create a table, each line includes pipe (|) symbols to separate columns of the table.
Dashes are also used to separate the headers from the rest of the table.

Here's an example of a table:

| Column 1 | Column 2  |
|----------|-----------|
| Row 1    | Data      |
| Row 2    | More data |

```markdown
| Column 1 | Column 2  |
|----------|-----------|
| Row 1    | Data      |
| Row 2    | More data |
```

You can align table content by placing `:` on the left, middle, or right side of the dashes underneath the header for that column:

| Left-Aligned | Center Aligned | Right-Aligned |
|:------------ |:--------------:| -------------:|
| Left text    | Center text    | Right text    |

```markdown
| Left-Aligned | Center Aligned | Right-Aligned |
|:------------ |:--------------:| -------------:|
| Left text    | Center text    | Right text    |
```


## Footnotes
In GitHub, you can reference a footnote by writing `[^1]` like this [^1].

[^1]: This is the first footnote.
