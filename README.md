# Markdown Syntax Guide

### Headers
```
    # h1
    ## h2
    ### h3
    #### h4
    ##### h5
    ###### h6

    Can also use:

    h1
    =
    h2
    -
```

### Text Effects
```
   *for italics*
   _another way to do italics_
   **for bold text**
   __another way to do bold text__
   **combining bold text and _italized text_**
```

### Horizontal Rule
Use either - * or _ 3x to create a hr


### Unordered Lists
```
    * Item 1
    * Item 2
        * sub item a
        * sub item b
```

### Ordered Lists
```
    1. Item 1
        * sub item a
        * sub item b
    2. Item 2
    3. Item 3        
```

### Blockquotes
```
    Someone said:

    > An apple a day keeps the doctor away!
    > or was it oranges?
    >> this is how you do blockquote within blockquote.
```

### Hyperlinks
```
    Use the full http url for e.g. http://www.google.com
    (or)
    [Hyperlink text](http://www.google.com)
```

### Images
```
    ![Alt text for image](url to the image)
```

### Escape Sequences
Use backslash to escape special characters
for e.g. 
```
    doing this -> \*asterisks*
    will print this -> *asterisks* instead of making it italics
```

works with most of the special char sequences like \ ` * _ { } [ ] ( ) # + - . ! etc.

### Code Blocks
Use backticks for single line of code. for e.g. \`console.log('hello world');`

likewise use ` 3x or 4 spaces for multiline or fenced code blocks. for e.g:

\```javascript
    function greet(message) {
        alert(message);
    }
\```

Adding the language name after \``` provides syntax highlighting.

### Tables
- use - char to separate th from tbody
- likewise use | char to separate cols
- use : for col alignment
    - for e.g. :-----: does center
    - ----: does right align 

here's an example
```
    Name    |   Location
    -----       :--------:
    Jake    |   FL
    Rob     |   WI
    Sally   |   TX
```
### Github Flavored Markdown (GFM) provides additional features like

- @Mentions
- Issue References
- Emojis
- Task lists
- Tables etc.
