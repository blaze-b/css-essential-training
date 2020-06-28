# CSS Basics (CASCADING STYLE SCHEETS)
- Appearance and styling of the html documents
- Referencing CSS in three ways: External, Inline and Internal</br>
&nbsp;&nbsp;&nbsp;&nbsp; a) External Referencing is done by using a seperate .css file, element used is link inside the head element</br> 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; `<link rel="stylesheet" href ="css/styles.css">`</br> no need of type="text/css" Multiple css can be used</br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Usage of the `@import` method example: `@import url('/styles/layout.css');`</br>chan  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; `<style> @import url('/basics/style.css'); </style>`</br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; in the head, This slows down the loading and is not used frequently</br>
&nbsp;&nbsp;&nbsp;&nbsp; b) Usage in the inline css, `<p style="color: red;">Hi</p>`</br>
&nbsp;&nbsp;&nbsp;&nbsp; c) Internal css, `<style> h1 {color: green;} </style>`