# Ultimate Beginner's Guide to Markdown

# # Heading 1
## ## Heading 2
### ### Heading 3
#### #### Heading 4

## Line Breaks 
You can create a line break by pressing 'Enter' twice and then entering '---' like below.

---

## Paragraphs
If you press 'Enter' once and continue writing,
it continues the sentence.

But if you press 'Enter' twice before continuing to write,

you create a new paragraph.

## Lists
You can create a bulleted list by using one asterisk followed by a space:
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

### Todo lists
To create a todo list, you include [ ] or [x] representing unchecked/checked to your unordered list:
* [ ] Unchecked item
* [x] Checked item

## Emphasis
Surrounding your text with:
* 1 set of asterisks (*) ➡️  *italics*
* 2 sets of asterisks (*) ➡️ **bold**
* 3 sets of asterisks (*) ➡️ ***bold and italics***
* 2 sets of '~' ➡️ ~~strikethrough~~
* `<ins> </ins>` ➡️ <ins>underline</ins>
* `<sup> </sup>` ➡️ for <sup>superscript</sup>
* `<sub> </sub>` ➡️ for <sub>subscript</sub>

## Blockquote
To create a blockquote, you start each line with a '>':

> If your blockquote has multiple paragraphs,
> 
> make sure you have any extra line with just '>' between the paragraphs.

## Code Blocks
You can add inline code by adding a set of backticks `inline code`.

If you want a block of code, surround it with three sets of backticks (`):
```bash
git add .
git commit -m "First commit"
git push
```

## Links
If you want to add a link, just add the url of the 

If you want to hyperlink text:
1. Add the text you want to be shown inside one set of brackets  [Link text]
2. Add the url inside one set of parentheses (link)

Here's an [example link to Google](https://www.google.com/)

## Images
To embed an image:
1. Add an exclamation point (!)
2. Add the text representing the image inside one set of brackets  [Alternative text]
3. Add the url to the link inside one set of parentheses (url for image)

Here's an example of the Markdown logo:
![Markdown logo](https://cdn.commonmark.org/uploads/default/original/2X/3/366f3614de6996d79a131fdf9b41ed7d65cfe181.png)

## Footnotes
You can reference to a footnote putting ^1 inside brackets [^1]

[^1]: This is the first footnote.
