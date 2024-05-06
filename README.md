# Sezoo-on-github
Testing creating web pages from GitHub repository 

There is, as of this release, absolutely no content of any use in this repository and presented on this site. I am just exploring the basic features available. Hope you weren't expecting more...

Basically I'm exploring how to use markdown to create formatted documents.

There are quite a few online resources giving Markdown guides. Here's one:
https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax

This is a table in markdown
| column 1 heading | column 2 Heading | column 3 heading |
| :---- | :---: | ----: |
| left alignment | centre alignment | right alignment |
| in markdown I've created columns of different character widths | simple column text | but the table should render neatly |
| this table has very | simple formatting | but it looks like the rows get an alternate shading effect |
| At least that's  | what | the rendered view looks like on GitHub |


# Heading 1
This would be text after the first level 1 heading

This is code block:
```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```
And this code block declares the language being used (which enables the rendering software to highlight terms appropriately)
```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

## Heading 2
This would be text after a level 2 heading

Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.

    `{ my code }`

    Add as many paragraphs as you like.

### Heading 3
This would be text after a level 3 heading

This is an image
![Image from better ends article](https://github.com/sezoo-digital/Sezoo-on-github/blob/main/Better%20Ends%20-%20Jackie's%20busy%20life.png?raw=true) 

And this is another image file, this time in the image folder of the repository
![Image from image folder in the repository](https://github.com/sezoo-digital/Sezoo-on-github/blob/9d93971b7222b771787753f87e1563a8fc842d55/images/Towards%20better%20ends%20(1).png?raw=true)

The next markdown sequence should create a line across the page. I think the three "-" signs need to be separated by a blank line before and after to create a standalone line

---

Next I'll put "---" after some text

Term definitions
---

And now I'll try "---" before some text

---
This is some text

This is a term
: And this would be the text that offers a definition of the term. I'll add some more text to see how the formatting works when the lines get longer than a single line on a rendered page.
: This would be a second definition of the same term.

However GitHub markdown doesn't support this Markdown syntax, and apparently I need to use the HTML commands directly...

<dl>
  <dt>Lower cost</dt>
  <dd>The new version of this product costs significantly less than the previous one!</dd>
  <dt>Easier to use</dt>
  <dd>We've changed the product so that it's much easier to use!</dd>
</dl>

# More images

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
</picture>
