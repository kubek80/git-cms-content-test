# Markdown Showcase Document

## Basic Text Formatting

This is a paragraph with **bold text**, *italic text*, and ***bold italic text***. You can also use __underscores__ for bold and _underscores_ for italics.

This is ~~strikethrough~~ text.

## Headings
## TEST 2

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

## Lists

### Unordered Lists

* Item 1
* Item 2
  * Nested item 2.1
  * Nested item 2.2
* Item 3

### Ordered Lists

1. First item
2. Second item
   1. Nested item 2.1
   2. Nested item 2.2
3. Third item

### Task Lists

- [x] Completed task
- [ ] Incomplete task
- [ ] Another task

## Links

[Link to Google](https://www.google.com)
[Link with title](https://www.example.com "Example Website")

## Images

![Alt text for image](https://via.placeholder.com/150 "Image Title")

## Blockquotes

> This is a blockquote
> 
> It can span multiple lines
>
>> Nested blockquotes are possible too

## Code

Inline `code` looks like this.

```javascript
// Code block with syntax highlighting
function helloWorld() {
  console.log("Hello, world!");
}
```

## Tables

| Header 1 | Header 2 | Header 3 |
|----------|:--------:|---------:|
| Left     | Center   | Right    |
| aligned  | aligned  | aligned  |
| cell     | cell     | cell     |

## Horizontal Rules

---

***

___

## Escaping Characters

\*This text is surrounded by asterisks but not italic\*

## Footnotes

Here's a sentence with a footnote.[^1]

[^1]: This is the footnote.

## Definition Lists

Term
: Definition 1
: Definition 2

## HTML in Markdown

<details>
  <summary>Click to expand!</summary>
  
  ### This content is hidden until clicked
  
  You can use HTML within Markdown for advanced formatting needs.
</details>

## LaTeX Math (if supported)

Inline math: $E=mc^2$

Block math:

$$
\frac{d}{dx}(x^n) = nx^{n-1}
$$

## Emojis (in many Markdown processors)

:smile: :heart: :thumbsup: :rocket:

## Highlights (in some Markdown flavors)

==This text is highlighted== (not supported in all Markdown processors)

## Diagrams (in some Markdown processors like Mermaid)

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

## References

* [Markdown Guide](https://www.markdownguide.org/)
* [GitHub Flavored Markdown](https://github.github.com/gfm/)
