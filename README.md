# Web-Development
Lets's start learning Web Development
# HTML
#### Hyper Text Markup Language
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
<a href="contact"> Contact us </a> <!-- contact page opens in same tab -->
<a href="contact" target="blank"> Contact us </a> <!-- Opens in a new tab -->
```
You can even wrap an image in an anchor tag: (img tag is used to add images)
```
<a href="https://example.com">
  <img src="logo.png" alt="Logo">
</a>
```
### image tag 
it is used to add image on html file.<br>
```
<img src="logo.png">
```
### Video tag
It is uesd to play video in html file.<br>
```
<video src="hello.mp4">Click</video>
````
<b> Attribute for video</b><br>
Width : to adjust width of a video <br>
We can use autoplay/loop to autoplay or loop the video.
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
### Header tag
It is a semantic element used to define introductory content or navigational links for a webpage or a section. It helps structure your HTML meaningfully.
```
<header>
  <h1>Welcome to My Website</h1>
  <nav>
    <a href="home">Home</a>
    <a href="about">About</a>
    <a href="contact">Contact</a>
  </nav>
</header>
```
### Main tag
It represents the central content of a webpage—the part that’s directly related to the page’s purpose.
Inside the main tag we insert the following tags:
```
<main> <!-- The main opening tag -->
<section> <!-- A page section --> </section>
<article> <!-- A self contained content --> </article>
<aside> <!-- It as a sidebar, a callout box, or a place for extra info that complements the core material. -->
</main> <!-- The main closing tag -->
```
### Div tag 
It used as a container for other elements. div is a block level element( always takes full width).
```
<div>I am box </div>
```
### Span tag
It is an inline container (takes as much width as necessary).
```
<span> I am a web developer </span>
```
### List tag
It is used to display content which represents a list.<br>
Unordered list : Used to list unordered items.
```
<ur>
<li> Home</li>
<li> About</li>
</ur>
```
Ordered list : Used to list ordered items.
```
<ol>
<li> Phone </li>
<li> Pc </li>
<li> Laptop</li>
</ol>
```
### Tables tag 
It used to create a tabular data .<br>
<b> tr tag:</b> used to display table row <br>
<b> th tag :</b> used to display table heading <br>
<b> td tag :</b> used to display table data <br>
<b> caption tag :</b>
used to add caption in table <br>
<b> colspan attribute :</b> used to cells spanning multiple table
```
<th colspan="3">Hello</th>
```
### Forms 
It is used to collect input from the user.
```
<form>
-- Element of the form--
</form>
```
 <b>Common Form Elements</b>
 ```
- <input> – text fields, checkboxes, radio buttons
- <textarea> – multi-line text input
- <select> – dropdown menus
- <button> – clickable buttons
- <label> – labels for inputs
- <fieldset> and <legend> – group related elements
```
<b>Example</b>
```
<form action="/login" method="POST">
  <label for="username">Username:</label>
  <input type="text" id="username" name="username" required>

  <label for="password">Password:</label>
  <input type="password" id="password" name="password" required>

  <button type="submit">Login</button>
</form>
```
### Comments in html
Comments in html are used to mark text which should not be parsed . They can help document the source code.
```
<!-- HTML comments -->
```
## Search Engine Optimization (SEO)
🔍 What SEO Actually Does
SEO helps search engines:
- Understand your content
- Index your pages properly
- Rank your site higher for relevant search queries<br>
This means more traffic, better visibility, and ideally, more conversions.<br>
#### you can implement SEO using the following techniques:
- Set the title very nice & to the point <br>
- Set the meta description 
``` <meta name="description" content="...">```
- Set a nice URL slug
- Set the meta keywords tag
- Set the meta author tag
  ``` <meta name="author" content="Video">```
- Set a faricon
- Compress images & other resources
- Remove unused HTML/CSS & Js files + Compress them
- Add alt test to images.
# CSS
#### Cascading Style Sheets 
HTML is just an skelatal layout of a website. We need CSS to design a website, add styles to it and make it look beautiful.
##### First line of CSS 
Create a .css file inside your directory and add it to your HTML.Add the following line to your CSS.
```
body {
       background-color: red;
       }
<!-- This will make your page background as red.-->
```
#### HTML id and class attributes
- When an html element is given an id, it serves as a unique identifier for that element.
- When an html element is given a class, it now belongs to that class.
- more than one elements can belong to a single class but every element must have a unique id.
We can add multiple classes to an element like this
```
<div
     id="first" class="C1 C2 C3">
</div>
```
#### Three ways to add CSS to HTML
- style tag : adding (<style>... </style>) to html
- Inline CSS : adding CSS using Style attribute
- External CSS: adding a stylesheet(.css) to html using link tag.
### CSS Selector
It is used to select an html elements for styling
```
body{
color:red;
background:pink;
}
<!-- Here body is a selector-->
```
#### 1. Element Selector
It is used to select an element based of the tagname. <br>
For example:
```
h2{
   color:blue;
}
<!-- here h2 is a selector-->
```
#### 2. id Selector
It is used to select an element with a given id .<br>
For example:
```
#first{
       background:black;
        color:white;
        }
<!-- here # is used to target by id-->
```
#### 3.Class Selector
It is used to select an element with a given class.<br>
For example:
```
.red {
      background:red;
      }
<!-- here .(dot) is used to target by class-->
```
#### 4. Universal Selector
(*)can be used as a universal selector to select all the elements.
```
* {
   margin:0px;
   padding:0px;
    }
```
#### Imp notes
- We can use group selectors like this:
```
   h1, h2, h3, div{
       color:blue;
       }
```
- We can use element class as a selector like this:
```
p.red {
     color:red;
     }
<!-- all paragraphs of red will get color of red-->
```

     

