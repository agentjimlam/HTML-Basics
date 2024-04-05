<h1>Learning HTML Codecademy HTML module</h1>

HTML = HyperText Markup Language


<body>
   <p> 
     HTML is composed of elements. These elements structure the webpage and define its content. Let’s take a look at how they’re written.
     The diagram to the right displays an HTML paragraph element. As we can see, the paragraph element is made up of:

<ol>
  <li>An opening tag "(p)"  </li>
  <li>The content (“Hello World!” text) </li>
  <li>A closing tag (/p) </li>
</ol>

A tag and the content between it is called an HTML element. There are many tags that we can use to organize and display text and other types of content, like images.

Let’s quickly review each part of the element pictured:

HTML element (or simply, element) — a unit of content in an HTML document formed by HTML tags and the text or media it contains.

HTML Tag — the element name, surrounded by an opening (<) and closing (>) angle bracket.

Opening Tag — the first HTML tag used to start an HTML element. The tag type is surrounded by opening and closing angle brackets.

Content — The information (text or other elements) contained between the opening and closing tags of an HTML element.

Closing tag — the second HTML tag used to end an HTML element. Closing tags have a forward slash (/) inside of them, directly after the left angle bracket.

    </p>

   <p> I put the rest of notes, review notes in comment tag. Open editor to view </p>
<!--
   Let’s review what you’ve learned so far:

   HTML stands for HyperText Markup Language and is used to create the structure and content of a webpage.
   Most HTML elements contain opening and closing tags with raw text or other HTML tags between them.
   HTML elements can be nested inside other elements. The enclosed element is the child of the enclosing parent element.
   Any visible content should be placed within the opening and closing <body> tags.
   Headings and sub-headings, <h1> to <h6> tags, are used to provide titles for sections of content.
   <p>, <span> and <div> tags specify text or blocks.
   The <em> and <strong> tags are used to emphasize text.
   Line breaks are created with the <br> tag.
   Ordered lists (<ol>) are numbered and unordered lists (<ul>) are bulleted.
   Images (<img>) and videos (<video>) can be added by linking to an existing source.
-->

<p>How to print special characters, see comment tag</p>

<!--
Special characters in HTML, such as '<', '>', '"' and '&' can be printed using the following format:

&name;
where name would be replaced by a character name. The most common would then be

&lt;   =   <    (less than)
&gt;   =   >    (greater than)
&amp;  =   &    (ampersand)
&quot; =   "    (double quote)

So to write <html> you would write in HTML: &lt;html&gt;
-->




<p>Let’s review what you’ve learned this lesson:
<ol>
   <li>The <!DOCTYPE html> declaration should always be the first line of code in your HTML files. This lets the browser know what version of HTML to expect.</li>
   <li>The <html> element will contain all of your HTML code.</li>
   <li>Information about the web page, like the title, belongs within the <head> of the page.</li>
   <li>You can add a title to your web page by using the <title> element, inside of the head.</li>
   <li>A webpage’s title appears in a browser’s tab.</li>
   <li>Anchor tags (&lt;a&gt;) are used to link to internal pages, external pages or content on the same page.</li>
   <li>You can create sections on a webpage and jump to them using <a> tags and adding ids to the elements you wish to jump to.</li>
   <li>Whitespace between HTML elements helps make code easier to read while not changing how elements appear in the browser.</li>
   <li>Indentation also helps make code easier to read. It makes parent-child relationships visible.</li>
   <li>Comments are written in HTML using the following syntax: <!-- comment -->.</li>
</p>


<p>
   Introduction to Tables
There are many websites on the Internet that display information like stock prices, sports scores, invoice data, and more. This data is tabular in nature, meaning that a table is often the best way of presenting the data.
In this part of the course, we’ll learn how to use the HTML <table> element to present information in a two-dimensional table to the users.

Let’s get started!
   
</p>


<div id="table">
<table>
  <tr> <!-- Row 1 -->
    <th></th>
    <th>Saturday</th>
    <th>Sunday</th>
  </tr>
  <tr> <!-- Row 2 -->
    <th>Morning</th>
    <td rowspan="2">Work</td>
    <td rowspan="3">Relax</td>
  </tr>
  <tr> <!-- Row 3 -->
    <th>Afternoon</th>
  </tr>
  <tr> <!-- Row 4 -->
    <th>Evening</th>
    <td>Dinner</td>
  </tr>
</table>
</div>




 </body>
