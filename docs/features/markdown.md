---
icon: simple/markdown
---

# Markdown Examples

Learn how to write rich content with Markdown extensions supported by Zensical.

---

## Text Formatting

```
**bold text**
*italic text*
***bold and italic***
~~strikethrough~~
`inline code`
```

**Result:**

**bold text**  
*italic text*  
***bold and italic***  
~~strikethrough~~  
`inline code`

---

## Headers

```
# H1 Header
## H2 Header
### H3 Header
#### H4 Header
##### H5 Header
###### H6 Header
```

---

## Links and Images

```
[Link text](https://example.com)
[Link with title](https://example.com "Hover title")
![Alt text](image.jpg)
![Image with title](image.jpg "Image title")
```

---

## Lists

### Unordered Lists

```
- Item 1
- Item 2
  - Nested item
  - Another nested
- Item 3
```

### Ordered Lists

```
1. First item
2. Second item
3. Third item
```

---

## Blockquotes

```
> This is a blockquote
> Multiple lines

>> Nested quote
```

**Result:**

> This is a blockquote
> Multiple lines

>> Nested quote

---

## Code Blocks

````
```python
def greet(name):
    """Greet a person."""
    return f"Hello, {name}!"

# Call the function
print(greet("World"))
```
````

---

## Tables

```
| Header 1 | Header 2 | Header 3 |
|----------|----------|----------|
| Row 1    | Data     | Data     |
| Row 2    | Data     | Data     |
| Row 3    | Data     | Data     |
```

**Result:**

| Header 1 | Header 2 | Header 3 |
|----------|----------|----------|
| Row 1    | Data     | Data     |
| Row 2    | Data     | Data     |
| Row 3    | Data     | Data     |

---

## Task Lists

```
- [x] Completed task
- [ ] Incomplete task
- [ ] Another task
```

**Result:**

- [x] Completed task
- [ ] Incomplete task
- [ ] Another task

---

## Footnotes

```
Here is a sentence with a footnote.[^1]

[^1]: This is the footnote content.
```

---

## Abbreviations

```
The HTML spec is maintained by the W3C.

*[HTML]: HyperText Markup Language
*[W3C]: World Wide Web Consortium
```

---

**Learn more:**
- [Features Overview](../index.md)
- [Demo Components](components.md)
