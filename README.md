## CSS Basics (CASCADING STYLE SCHEETS)

- Appearance and styling of the html documents

### [REFERENCE DOC](https://developer.mozilla.org/en-US/docs/Web/CSS)

## HTML and CSS

- HTML
  - It gives the structure of content
  - Semantic meaning

- CSS
  - Appearance
  - Styling


## Referencing CSS in three ways: External, Inline, Internal

- External Referencing is done by using a seperate .css file, 
    - Element used is link inside the head element`<link rel="stylesheet" href ="css/styles.css">` no need of type="text/css", Multiple css can also be used, 
    - Usage of the `@import` method example: `@import url('/styles/layout.css');` in the styles.css and `<style>@import url("../css/styles.css");</style>`,
    - Style `<style> @import url('/basics/style.css'); </style>` in the head, This slows down the loading and is not used frequently
- Usage in the inline css, `<p style="color: red;">Hi</p>`
- Internal css, `<style> h1 {color: green;} </style>`


### [IPSUM TEXTS](https://meettheipsums.com/)

### Image Optimization

- [SHOPIFY LINK](https://www.shopify.in/blog/7412852-10-must-know-image-optimization-tips)
- Retina Display:
  - TM by Apple
  - Retina = high pixel display
- Pixel Density:
  - Refers to the number of pixels within a space
  - Measured in pixel per inch(PPI) or dots per inch (DPI)
- Project Images:
  - Project Thumbnails = 600px width
  - Background images = 1400 px to 1200 px width

### Relative paths:

- When linking the same folder: `<link rel="stylesheet" href="style.css">`
- When different paths : `<link rel="stylesheet" href="/css/style.css">`

### Absolute paths:

- It refers to a resource located on a server: `<a href="http://website.com"></a>`, [Photo picker Website](https://picsum.photos/)

### CSS Specifications

- World wide web consortium(W3C) (https://www.w3.org/Style/CSS/Overview.en.html)

### CSS Syntax

- `img {width: 300px}` img = selector, {width: 300px} declaration, with property and value
- Short hand declaration
      .short-hand{
        padding-top: 10px;
        padding-right: 5px;
        padding-bottom: 10px;
        padding-left: 5px;
      }
- Long hand
      .long-hand{
        padding: 10px 5px;
      }
- Commenet /* */
- [Code Guide Website](https://codeguide.co/)
