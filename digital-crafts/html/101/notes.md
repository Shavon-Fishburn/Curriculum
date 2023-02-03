# HTML 101

## HTML forms the structure of all web pages

HTML -> hyper text markup language

The `<head>` tag configures the page and is not rendered by the browser.
Thr `<title>` tag contains the name of the page and is rendered in the browser's tab.
Tags that have opening and closing elements are not container elements and are called self-closing tags (` />).
To make reading an HTML file easier, lines are nsted within their parent element.
Browsers read HTML and in a sense, HTML is like a big long string.
Browsers can read files or you can start a server in VS Code with **Go Live**.


### Some of the most common elements are
#### semantic elements include
```
<div> - generic containmg element
<ul>- undordered list
<ol> - ordered list
<li> - list item
<header>- the header of the page
<main> - the main area of the page
<body> - contains all of th rendering HTML elements
<footer> - the footer area of the page
<nav> - contains navigation elements, ususally found inside of `<header>`
<p> - used for paragraphs of text
<img /> - used for images ( note this is self-closing), must have `src` attribute
<a> - anchor tag, used to hyperlink elements with th e`href` attribute
<h1> - header text (largest)
<h2> - header text
<h3> - header text
<h4> - header text
<h5> - header text
<h6> - header text (smallest)
```
### generic elements include
```
<div> - generic containing element
<section> - defines a section for child elements
```
#### tags used inside of `<head>`
<link> - used to link a stylesheet, only found in the `<head>`
