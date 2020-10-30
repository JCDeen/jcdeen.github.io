# Markdown Cheat Sheet

Thanks for visiting [The Markdown Guide](https://www.markdownguide.org)!

This Markdown cheat sheet provides a quick overview of all the Markdown syntax elements. It can’t cover every edge case, so if you need more information about any of these elements, refer to the reference guides for [basic syntax](https://www.markdownguide.org/basic-syntax) and [extended syntax](https://www.markdownguide.org/extended-syntax).

## Basic Syntax

These are the elements outlined in John Gruber’s original design document. All Markdown applications support these elements.

### Heading

*Use these* 

\# H1\
\## H2\
\### H3  

*to get these*  
# H1 
## H2   
### H3  

### Bold
\*\*bold tex\t*\*\
**bold text**

### Italic
\\*italicized text*\
*italicized text*

### Blockquote
\> blockquote  
> blockquote

### Ordered List

1. First item
2. Second item
3. Third item

### Unordered List

- First item
- Second item
- Third item

### Code

`code`

### Horizontal Rule

---

### Link

[the link title](https://www.example.com)

### Image

![alt text for the image](image.jpg)

## Extended Syntax

These elements extend the basic syntax by adding additional features. Not all Markdown applications support these elements.

### Table
Use this  

\| Syntax | Description |\
\| ----------- | ----------- |\
\| Header | Title |\
\| Paragraph | Text |  

to get this  

| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |  

### Fenced Code Block

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

### Footnote

Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.

### Heading ID

### My Great Heading {#custom-id}

### Definition List

term
: definition

### Strikethrough
Use this  
\~~The world is flat.~~  
to get this  
~~The world is flat.~~

### Task List

\- [x] Write the press release\
\- [ ] Update the website\
\- [ ] Contact the media  

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media
