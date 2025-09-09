# Web-Development
Lets's start learning Web Development
## HTML
#### Hyper Text Markup Language <br>
It's used for defining layout of a web page.
### A basic HTML page 
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Our First Website</title>
</head>
<body>
    
</body>
</html>
```
## Tags in Html
 ### 1. <! Doctype html>
It specifies this is an html document.
 ### 2. html tag
Root of an html page 
### 3. head tag 
It contains page metadata
### 4. title tag
It contains title
### 5. body tag
The main body of the page. We can add elements inside the body tag to define the page layout.
```
<body> <!-- Opening tag-->
    content....
</body> <!-- Closing tag-->
```
### Anchor tag
Use to add links 
```
<a href="www.du.ac.in"> Click me </a>
```
You can even wrap an image in an anchor tag: (img tag is used to add images)
```
<a href="https://example.com">
  <img src="logo.png" alt="Logo">
</a>
```
### heading tag
It is used to mark heading . From h1 to h6, we have tags for the most important to the least least important.
```
<h1>Most important heading</h1>
<h2>second most important heading</h2>
<h3>third most important heading</h3>
<h4>fourth most important heading</h4>
<h5>fifth most important heading</h5>
<h6>least important heading</h6>
```
### the paragraph tag
It is used to add paragraphs to an html page
```
<p>This is a paragraph</p>
```
### Bold, Italic and Underlined tag
```
<b>This is bold</b>
<i>This is italic</i>
<u>This is underline</u>
```
### br tag
It is used to create line break 
```
Hello, this is my first webpage.<br> Let's make it cool.
```
### big and small tags
We can make a text a bit larger and a bit smaller using big and small tags respectively.
```
 <p>This is <big>big text</big> and this is <small>small text</small>.</p>
```
### hr tag
It is used to insert a horizontal rule—a visual line that separates sections of content.
```
<p>Introduction</p>
<hr>
<p>Details</p>
```
### pre tag
It is used to display preformatted text, meaning the browser will preserve spaces, tabs, and line breaks exactly as they appear in the source code.

```
<pre>
  Line 1:     Indented
  Line 2:     Still indented
  Line 3:     Preserved spacing!
</pre>
```
### subscript and superscript
The <sub> tag makes text appear slightly below the normal line.
```
- Chemical formulas: H<sub>2</sub>O
```
The <sup> tag makes text appear slightly above the normal line.
```
 Exponents: x<sup>2</sup>
```
### Comments in html
Comments in html are used to mark text which should not be parsed . They can help document the source code.
```
<!-- HTML comments -->
```
