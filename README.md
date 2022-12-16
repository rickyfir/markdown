# Getting Started

_An overview of Markdown, how it works, and what you can do with it._

---

## What is markdown?

**Markdown** is a lightweight markup language that you can use to add formatting elements to plaintext text documents. Created by [John Gruber](https://en.wikipedia.org/wiki/John_Gruber) in 2004.

---

## Why use markdown?

There are several reason why people use markdown instead of WYSIWYG editors.

- Markdown can be used for everything. People use it to create website, documents, notes, books, presentations, email message, and technical documentation.
- Markdown is portable. Files containing markdown-formatted text can be opened using virtually any application. If you decide you don't like the markdown application you're currently using, you can import your markdown files into another markdown application. That's in stark contrast to word processing applications like Microsoft Word that lack your content into a proprietary file format.
- Markdown is platform independent. You can create markdown-formatted text on any device running any operating system.
- Markdown is future proof. Even if the application you're using stops working at some point in the future, you'll still able to read your markdown-formatted text using a text editing application. This is an important consideration when it comes to books, university theses, and other milestone documents that need to be preserved indefinitely.
- Markdown is everywhere. Websites like Reddit and Github support markdown, and lots of desktop and web-based applications support it.

---

# Basic syntax

These are the elements outlined in **Jhon Gruber** original design document.
All Markdown application support these elements.
| Element | Markdown syntax |
| --------- | ------------------|
| Heading | # H1 |
| | ## H2 |
| | ### H3 |
| Bold | **bold text** |
| Italic | _italicized text_ |
| Blockquote | > blockquote |
| Ordered list | 1. first item |
| | 2. second item |
| | 3. third item |
| Unordered list | - first item |
| | - second item |
| | - thrid item |
| Code | `code` |
| Horizontal rule | --- |
| Link | `[title](https://www.example.com)` |
| Image | `![alt text](image.jpg)` |

---

# Extended syntax

These elements extended the basic syntax by adding additional features.
Not all markdown applications support these elements.
| Element | Markdown syntax |
| ------ | ------|
| Table | `edit this markdown!`| Syntax | Description | |
| | `edit this markdown!`| ----------- | ----------- | |
| | `edit this markdown!`| Header | Title | |
| | `edit this markdown!`| Paragraph | Text | |
| Fenced code block | ` ``` ` |
| | `{` |
| |`"firstName": "Jhon",`|
| |`"lastName": "Smith",`|
| | `"Age": 25`|
| | `}` |
| | ` ``` ` |
| Footnote | Here's a sentence with a footnot.[^1] |
| | [^1]: This is the footnote. |
| Heading ID | ### My great heading {#custome-id} |
| Definition list | term |
| | : definition |
| Strikethrough | `~~the world is flat.~~` |
| Task list | - [x] write the press release |
| | - [ ] update the website |
| | - [ ] contact the media |
| emoji | That is so funny! :joy: |
| highlight | I need to highlight these `==very important words==`. |
| Subscript | `H~2~O` |
| Superscript | `X^2^` |
