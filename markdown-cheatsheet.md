# Markdown Cheatsheet

## **HEADINGS**

<!-- Headings -->

# Heading 1 \#

## Heading 2 \#\#

### Heading 3 \#\#\#

#### Heading 4 \#\#\#\#

##### Heading 5 \#\#\#\#\#

###### Heading 6 \#\#\#\#\#\#

## **STYLES**

<!-- Italics -->

_This text_ is italic: \_text\_

<!-- Strong -->

**This text** is strong: \*\*text\*\*

<!-- Strikethrough -->

~~This text~~ is strikethrough: \~~text\~~

## **BREAK LINES**

<!-- Horizontal Rule -->

Horizontal rule with 3 hyphens: ( \-\-\- )

---

OR with 3 underscores: ( \_\_\_ )

---

<!-- Character scape -->

Character scape with \\
E.g. \*\*This is how you write bold text without being bold.\*\*

## **LINKS AND IMAGES**

<!-- Links -->

[This is a link to google.com](www.google.com): The text goes inside square brackets \[ \] followed by the link inside parenthesis \( \)

[This is a link to google.com with link description on roll-over](www.google.com "www.google.com"): The text goes inside square brackets \[ \] followed by the link inside parenthesis \( \) and the roll-over text inside quotes \" \" and inside the link's parenthesis.

<!-- Images -->

![Markdown Logo](https://markdown-here.com/img/icon256.png)

\!\[ Image alt text\]\(imageURL\)

## **LISTS**

<!-- UL -->

- item 1: using \-
- item 2
- item 3
  - nested item 1: using indentation and \-
  - nested item 2

<!-- OL -->

1. item 1: using number folled by a dot ( 1\. text)
1. item 2
1. item 3

## **QUOTES AND CODE BLOCKS**

<!-- Blockquote -->

> This is a block quote, using ( \> ) at the begining of the line

<!-- Inline Code Block -->

`<p>This is a paragraph</p>`, , using backtick ( ` ) at the beginning and end of the line.

<!-- Code Blocks -->

Use three backticks ( \`\`\` ) at the beginning and end of the block. For specific languages, include the name of the language after the initial backtics e.g. ( \`\`\`javascript )

```bash
    npm install

    npm start
```

```javascript
function add(num1, num2) {
  return num1 + num2;
}
```

```python
def add(num1, num2) {
  return num1 + num2;
}
```

## **TABLES**

<!-- Table -->

Using \| to separate the columns and \-\-\-\- to separate the rows
| Name | Email |
| -------- | --------------- |
| John Doe | john@gmail.com |
| Jane Doe | janen@gmail.com |

<!-- Task list -->

- [x] Task 1
- [x] Task 2
- [ ] Task 3

---

**Source:** [Traversy Media](https://www.youtube.com/watch?v=HUBNt18RFbo&t=40s)
