# Full Syntax Test (CommonMark + GFM) - Markdown rendering

## Text Formatting

**Bold**, *italic*, ***bold italic***  
~~Strikethrough~~  
==Highlight==  
`Inline code`  

<sub>Subscript</sub> and <sup>Superscript</sup> (HTML inline allowed)  

## Paragraphs & Line Breaks

This line ends with two spaces to create a line break.  
New paragraph starts here.

## Blockquotes

> Quote level 1  
>> Quote level 2  

## Horizontal Rules

---

***

___

## Lists

### Unordered

* Item 1
* Item 2
  * Nested item 2.1  
  * Nested item 2.2
* Item 3

### Ordered

1. First
2. Second  
   1. Nested 2.1  
   2. Nested 2.2  
3. Third

### Task Lists (GFM)

- [x] Completed task
- [ ] Incomplete
- [ ] Another
  - [x] Nested done
  - [ ] Nested incomplete

## Code

### Inline

`console.log("Hello")`

### Fenced Blocks

```js
function greet(name) {
  return `Hello, ${name}!`;
}
console.log(greet("world"));
```

```bash
echo "shell test"
```

```
Plain code block with no language
```

## Links

Standard: [Flowershow](https://flowershow.app)

Autolink (GFM auto-linking): https://flowershow.app

Reference link style:  
[Example][ref-1]

[ref-1]: https://flowershow.app "Flowershow Site"

Images:  
![Flowershow logo](../logo.jpg "Test image")

## Tables (GFM)

| Column A | Column B | Column C |
|---|:---:|---:|
| left | center | right |
| a | b | c |

## Footnotes (GFM)

Here is a footnote reference.[^1]

[^1]: This is the footnote text.

## HTML Blocks (allowed in CommonMark)

<div>
  <strong>Raw HTML block test</strong>
</div>

## Escape Characters

\*Not italic\*  
\# Not heading  
Backslash test: \\

## Emojis (GFM)

👍 🎉 ✅

## Definition List (not in CM/GFM but many parsers support)

Term  
: Definition text

## YouTube Link Autodetect

https://youtu.be/ZbQRlNm2dww
