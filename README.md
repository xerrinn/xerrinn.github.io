# xerrinn.github.io
<!--DOCTYPE html-->
<html lang="en-US">
<head>
    <style>
        body{background-color:rgb(255,228,225);}
        h1{color:blue;}
      
    a:link{
    color:green;
    background-color:transparent;
    text-decoration:none;}

    a:visited{
    color:tomato;
    background-color:transparent;
    text-decoration:none;}

    a:active{
    color:yellow;
    background-color:transparent;
    text-decoration:underlined;}
    
    div{
        background-image:url(https://f8n-ipfs-production.imgix.net/QmeQ6c5HdnEDcheHmWuKWdwMHBBZg1eGpgV5h3H2MyvdzR/nft.jpg?q=100&w=2560&fit=fill);
    }
    
    table, th, td {
      width:500px;
      border: 1px solid black;
      border-collapse: collapse;
    }
    th, td {
      padding: 15px;
      text-align: left;
    }
    
    #t1{
      width:500px;
      background-color:powderblue;
    }
    
    #t01 tr:nth-child(even) {
      background-color: #eee;
    }
    
    #t01 tr:nth-child(odd) {
      background-color: #fff;
    }
    
    #t01 th {
      background-color: black;
      color: white;
    }
    
    #ul {
     list-style-type: none;
     margin: 0;
     padding: 0;
     overflow: hidden;
     background-color:black;
    }

    #l1 a{
      float: right;
      display: block;
      color: white;
      text-align: center;
      padding: 16px;
      text-decoration: none;
    }

    #l1 a:hover {
      background-color: tomato;
    }
    
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    </style>
    <title>Page Title</title> 
</head>
<body style="background-color:mistyrose;">
  
<h2>Navigation Menu</h2>
<p>In this example, we use CSS to style the list horizontally, to create a navigation menu:</p>

<ul id="ul">
  <li id="l1"><a href="#home">Home</a></li>
  <li id="l1"><a href="#news">News</a></li>
  <li id="l1"><a href="#contact">Contact</a></li>
  <li id="l1"><a href="#about">About</a></li>
</ul>

<h1 style="text-align:center;font-size:60px;background-color:Powderblue">This is a heading</h1>
<p style="color:tomato;font-family:verdana;font-size:150%;">This is a red paragraph in verdana font in 150% size</p>
<p style="border:2px solid violet;">This is another paragraph with border</p>
<p style="background-color:rgba(255,99,71,0.5)">This is a sentence.RGBA color values are an extension of RGB color values with an Alpha channel- whih specifies the opacity for a color.<br/>
This is another sentence with a line break.<br/>
HSL stands for hue, saturation and lightness. HSLA color values are an extension of HSL with an Alpha channel.<br/>
hue is a degree on the color wheel from 0 to 360. 0 is red, 120 is green and 240 is blue<br/>
Saturation is a percentage value, 0% means a shade of gray and 100% is the full color.<br/>
Lightness is also a percentage value, 0% is black and 100% is white<br/>
This is a sentence<hr>
Above is a horizontal rule</p>

<h2> The pre element</h2>
<p>The text inside a pre element is displayed in a fixed width font (usually courier) and it preserves both spaces and line breaks.</p>
<div style="background-image:url(https://f8n-ipfs-production.imgix.net/QmeQ6c5HdnEDcheHmWuKWdwMHBBZg1eGpgV5h3H2MyvdzR/nft.jpg?q=100&w=2560&fit=fill)">
<pre>
    My Bonnie lies over the ocean.
    My Bonnie lies over the sea.
    My Bonnie lies over the ocean.
    Oh, bring back my Bonnie to me
</pre>
</div>
<h2>Blockquote element</h2>
<blockquote cite="http://www.worldwildlife.org/who/index.html">
    For nearly 60 years, WWF has been protecting the future of nature. The world's leading conservation organization, WWF works in 100 countries and is supported by more than one million members in the United States and close to five million globally.
</blockquote>
<p>Browsers usually insert quotation marks around the q element.</p>
<p>WWF's goal is to: <q>Build a future where people live in harmony with nature.</q></p>

<h2>Abbreviation element</h2>
<div>
<p>The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>
<p>Marking up abbreviations can give useful information to browsers, translation systems and search-engines.</p>
</div>
<h2>Address element</h2>
<address>
Written by John Doe.<br>
Visit us at:<br>
Example.com<br>
Box 564, Disneyland<br>
USA
</address>

<h2>Citation element</h2>
<p><cite>The Scream</cite> by Edvard Munch. Painted in 1893.</p>

<h2>The Bi-directional Override</h2>
<bdo dir="rtl">This text will be written from right to left</bdo>

<h2 title="I'm a header">The title Attribute</h2>
<p title="I'm a tooltip">Mouse over this paragraph, to display the title attribute as a tooltip.</p>

<h2>Single or Double Quotes?</h2>
<p>In some situations, when the attribute value itself contains double quotes, it is necessary to use single quotes:</p>
<p>Move your mouse over the paragraphs below to see the effect:</p>
<p title='John "ShotGun" Nelson'>John with double quotes</p>
<p title="John 'ShotGun' Nelson">John with single quotes</p>

<a href="https://www.w3schools.com"target="_blank"> Visit W3Schools</a><br/>

<img src="/w3schools.jpg" alt="W3Schools.com" width="104" height="142">

<h2>Comment tags</h2> 
<!--Write your comment here -->
<p> This is another paragrah again<br/>
Comments are also great for debugging HTML, because you can comment out HTML lines of code, one at a time, to search for errors</p>
<!--Add more information here-->

<h2>Using CSS</h2>
<p> CSS stands for Cascading Style Sheets<br/>
CSS is used to format the layout of a webpage.<br/>
The word Cascading means that a style applied to a parent element will also apply to all children elements within the parent.So, if you set the color of the body text to "blue", all headings, paragraphs, and other text elements within the body will also get the same color, unless you specify something else.<br/>
CSS can be added to HTML in 3 ways
<pre>
    Inline- by using the style attribute inside html elements
    Internal- by using a style element in the <head> section
    External- by usiing a <link> element to link an external CSS file
</pre>
padding property defines a padding (space) between the text and border<br/>
margin property defines a margin (space) outside the border<br/>
External style sheet can be referenced with a full URL or with a path relative to the current web page<br/>

<h2>HTML links - hyperlinks</h2>
<p><pre>By default, links will appear as follow in all browser:
    -an unvisited link is underlined and blue
    -a visited link is underlined and purple
    -an active link is underlined and red
</pre></p>

<h3>The target attribute</h3>
<p>The target attributes specifies where to open the linked document<br/>
_self -Default. Opens the document in the same window/tab as it was clicked<br/>
_blank -Opens the document in a new window or tab<br/>
_parent -Opens the document in the parent frame<br/>
_top -Opens the document in the full body of the window
</p>

<h3>Absolute URL vs Relative URL </h3>
<p> Both are in href attribute. A local link (wihtin the same website) is relative URL (without https://www part)<br/>
An external link will use a full web address.</p>

<h3>Use an image as a Link</h3>
<a href="default.asp">
<img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;">
</a>
   
<h3>Link to an email address</h3>
<a href="mailto:someone@example.com">Send email</a>

<h3>Button as a link</h3>
<p>Click the button to go to the HTML tutorial.</p>
<button onclick="document.location='default.asp'">HTML Tutorial</button>

<h3>Link Titles</h3>
<p>The title attribute specifies extra information about an element. The information is most often shown as a tooltip text when the mouse moves over the element.</p>
<a href="https://www.w3schools.com/html/" title="Go to W3Schools HTML section">Visit our HTML Tutorial</a>

<h2 id="C4">Create a Bookmark in HTML</h2>
<a href="#C4">Jump to Create a Bookmark in HTML</a>

<h2>hTML images</h2>
<img src="img_chania.jpg" alt="Flowers in Chania"style="width:500px;height:600px;">

<h2>Floating Images</h2>
<p><strong>Float the image to the right:</strong></p>

<p>
<img src="smiley.gif" alt="Smiley face" style="float:right;width:42px;height:42px;">
A paragraph with a floating image. A paragraph with a floating image. A paragraph with a floating image.
</p>

<p><strong>Float the image to the left:</strong></p>
<p>
<img src="smiley.gif" alt="Smiley face" style="float:left;width:42px;height:42px;">
A paragraph with a floating image. A paragraph with a floating image. A paragraph with a floating image.  
</p>
<p>common image file types<br/>
.apng- Animated Portable Network Graphics
.gif- Graphics Interchange Format
.ico- Microsoft Icon
.jpg, .jpeg- Joint Photographic Expert Group image
.png- Portable Network Graphics
.svg- Scalable Vector Graphics </p>

<h2>HTML image maps</h2>
<p>Click on the computer, the phone, or the cup of coffee to go to a new page and read more about the topic:</p>
<img src="https://www.w3schools.com/html/workplace.jpg" alt="Workplace" usemap="#workmap" width="400" height="379">
<map name="workmap">
  <area shape="rect" coords="34,44,270,350" alt="Computer" href="https://en.wikipedia.org/wiki/Computer">
  <area shape="rect" coords="290,172,333,250" alt="Phone" href="https://en.wikipedia.org/wiki/Mobile_phone">
  <area shape="circle" coords="337,300,44" alt="Cup of coffee" href="https://en.wikipedia.org/wiki/Coffee">
</map>
<p>Lets try to  make croissant a clickable link</p>
<img src="https://www.w3schools.com/html/frenchfood.jpg" alt="croissant" usemap="#croissant" width="450" height="675">
<map name="croissant">
    <area shape="poly" coords="140,121,127,147,103,161,40,259,37,322,58,352,85,155,140,329,191,276,204,222,204,160,181,116" alt="a croissant" href="https://en.wikipedia.org/wiki/Croissant" onclick="myFunction()">
</map>
<script>
    function myFunction() {
        alert("You clicked the croissant!");
    }
</script>

<h2>The picture element</h2>
<picture>
  <source srcset="http://i.scbww.com/d/file/20171103/ceb8df0cfd08737ca7fdcb62b180eef6.jpg">
  <source srcset="http://i.scbww.com/d/file/20171103/2b228c27d6e3170636853351ecca2ba3.jpg">
  <img scr="http://i.scbww.com/d/file/20171103/347a6685a3968e74678c78bc76d7881a.jpg">
</picture>
<p>Resize the browser to see different versions of the picture loading at different viewport sizes. The browser looks for the first source element where the media query matches the user's current viewport width, and fetches the image specified in the scrset attribute. </p>
<p>The img element is required as the last child tag of the picture declaration block. The img element is used to provide backward compatibility for browsers that do not support the picture element, or if none of the source tags matched<br/>
<strong>Note</strong> The picture element is not supported in IE12 and earleir or Safari 9.0 and earlier</p>

<h3> trying another way (img)</h3>
<img
  scrset="
  http://i.scbww.com/d/file/20171103/ceb8df0cfd08737ca7fdcb62b180eef6.jpg,
  http://i.scbww.com/d/file/20171103/2b228c27d6e3170636853351ecca2ba3.jpg"
  src="http://i.scbww.com/d/file/20171103/347a6685a3968e74678c78bc76d7881a.jpg"
>
<p>attribute name=scrset, values=list of sources, notes=defines multiple sizes of the same image, allowing the browser to select the appropriate image source.<br/>
attribute name=src, notes=specifies the url of an image to be displayed<br/>
usually browser will use the src image, but under some specific stated circumstances, the browser will use the srcset that fits the screen size.</p>

<h2>HTML Table</h3>
<table id="t1">
  <caption> Name List</caption>
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
    <th colspan="2">Sex</th>
  </tr>
  <tr>
    <td>Chang</td>
    <td>Yan </td>
    <td>Female</td>
    <td>Female</td>
  </tr>
  <tr>
    <td>Lim</td>
    <td>Zhi </td>
    <td>Male</td>
  </tr>
  <tr>
    <td>Tong </td>
    <td>Yu  </td>
    <td>Female</td>
  </tr>
</table>

<table id="t01">
  <tr>
    <th>Name:</th>
    <td>Bill Gates</td>
  </tr>
  <tr>
    <th rowspan="2">Telephone:</th>
    <td>55577854</td>
  </tr>
  <tr>
    <td>55577855</td>
  </tr>
</table>
<p>Note that if the table has collapsed border, the border spacing has no effect</p>

<h2>An unordered HTML list</h2>

<ul style="list-style-type:circle"
</ul>
  <li>Coffee</li>
  <li>Tea</li>
    <ul style="list-style-type:square">
      <li>Black tea</li>
      <li>Green tea</li>
    </ul>
  <li>Milk</li>
</ul>
<p> The type of unordered list disc (the list will be mark as bullet, default), circle, square and none(the list wont be marked) </p>

<h2>An ordered HTML list</h2>
<ol type="1" start="10">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
<p>The type=1 (numbered),A (A,B,C),a(a,b,c),I(I,II,III),i(i,ii,iii)<br/>
By using the "start", the list will start from the number you provided<p>
  
<h2>A Description List</h2>

<dl>
  <dt>Coffee</dt>
  <dd>- black hot drink</dd>
  <dt>Milk</dt>
  <dd>- white cold drink</dd>
</dl>

<h2> HTML block and inline</h2>
<p>
Div -Defines a section in a document (block-level)<br/>
Span -Defines a section in a document (inline)<br/>
A block-level element always starts on a new line and takes up the full width available<br/>
An inline element does not start on a new line and it only takes up as much width as necessary<br/>
</p>

<h2>Use of The class Attribute in JavaScript</h2>
<p>Click the button to hide all elements with class name "city":</p>
<button onclick="myFunction()">Hide elements</button>

<h2 class="city">London</h2>
<p>London is the capital of England.</p>

<h2 class="city">Paris</h2>
<p>Paris is the capital of France.</p>

<h2 class="city">Tokyo</h2>
<p>Tokyo is the capital of Japan.</p>

<script>
function myFunction() {
  var x = document.getElementsByClassName("city");
  for (var i = 0; i < x.length; i++) {
    x[i].style.display = "none";
  }
}
</script>

<h2>HTML bookmarks with id and link</h2>
<h3>The difference between class and id</h3>
<p>A class name can be used by multiple HTML elements, while an id name must only be used by one HTML element within the page</p>

<body>

<p><a href="#C3">Jump to Chapter 3</a></p>
<p><a href="#C10">Jump to Chapter 10</a></p>

<h3>Chapter 1</h3>
<p>This chapter explains ba bla bla</p>

<h3>Chapter 2</h3>
<p>This chapter explains ba bla bla</p>

<h3 id="C3">Chapter 3</h3>
<p>This chapter explains ba bla bla</p>

<h3>Chapter 4</h3>
<p>This chapter explains ba bla bla</p>

<h3>Chapter 5</h3>
<p>This chapter explains ba bla bla</p>

<h3>Chapter 6</h3>
<p>This chapter explains ba bla bla</p>

<h3>Chapter 7</h3>
<p>This chapter explains ba bla bla</p>

<h3>Chapter 8</h3>
<p>This chapter explains ba bla bla</p>

<h3>Chapter 9</h3>
<p>This chapter explains ba bla bla</p>

<h3 id="C10">Chapter 10</h3>
<p>This chapter explains ba bla bla</p>

<h3>Chapter 11</h3>
<p>This chapter explains ba bla bla</p>

<h3>Chapter 12</h3>
<p>This chapter explains ba bla bla</p>

<h2>Using The id Attribute in JavaScript</h2>
<p>JavaScript can access an element with a specified id by using the getElementById() method:</p>

<h1 id="myHeader">Hello World!</h1>
<button onclick="displayResult()">Change text</button>

<script>
function displayResult() {
  document.getElementById("myHeader").innerHTML = "Have a nice day!";
}
</script>

<h2>Iframe in HTML</h2>
<iframe src="" width="1300" height="470" style="border:none;" title="Example of iframe"></iframe>

<h2>Iframe - Target for a Link</h2>
<iframe name="iframe_a" height="300px" width="100%" title="Iframe Example"></iframe>
<p><a href="" target="iframe_a">W3Schools.com</a></p>
<p>When the target attribute of a link matches the name of an iframe, the link will open in the iframe.</p>

<h2> MY first Javascript</h2>
<button type="button" onclick="document.getElementById('demo').innerHTML=Date()">Click me to display date and time</button>
<p id="demo"></p>

<h2> Use Javascript to write a HTML</h2>
<p id="try"></p>
<script>
  document.getElementById("try").innerHTML = "Hello JavaScript"
</script>

<h2>JavaScript can change content of a HTML</h2>
<button type="button" onclick="myFunction()">Click Me!</button>
<p id="demo">This is a demonstration.</p>
<script>
function myFunction() { 
  document.getElementById("demo").innerHTML = "Hello JavaScript!";
}
</script>

<h2 id="2">JavaScript can change the style of an HTML element.</h2>
<button type="button" onclick="myFunction()">Click Me!</button>
<script>
function myFunction() {
  document.getElementById("2").style.fontSize = "25px"; 
  document.getElementById("2").style.color = "red";
  document.getElementById("2").style.backgroundColor = "yellow";        
}
</script>

<h2>Javascript can change the src</h2>
<p>Here, a JavaScript changes the value of the src (source) attribute of an image.</p>
<script>
function image(aa) {
  var pic;
  if (aa == 0) {
    pic = "https://www.w3schools.com/html/pic_bulboff.gif";
  } else {
    pic = "https://www.w3schools.com/html/pic_bulbon.gif";
  }
  document.getElementById("2").src = pic;
}
</script>
<img id="2" src="https://www.w3schools.com/html/pic_bulboff.gif" width="100" height="180">
<p>
<button type="button" onclick="image(1)">Light On</button>
<button type="button" onclick="image(0)">Light Off</button>
</p>
<!--This can run on the website but not in this file, further investigation needed-->

<h2>HTML noscript </h2>
<p id="demo"></p>

<script>
document.getElementById("demo").innerHTML = "Hello JavaScript!";
</script>

<noscript>Sorry, your browser does not support JavaScript!</noscript>

<p>A browser without support for JavaScript will show the text written inside the noscript element.</p>

<h2>html base tags</h2>
<p>If you have all your images stored in a folder 'images/' which is in a location different from the HTML document,
you can avoid using <img src="images/pic1.jpg"> and  <img src = "images/pic2.jpg"> for each image and just do this: <base href="images/">
and use something like <img src="pic1.jpg"> <img src="pic2.jpg"> in all future relative URL references.<br/>
The base tag should be added under "head"
</p>


</body>
</html>
