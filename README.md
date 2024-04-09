<h1>Learning HTML Codecademy HTML module</h1>

<p>HTML = HyperText Markup Language :+1: </p>

<body>
   <p> 
     HTML is composed of elements. These elements structure the webpage and define its content. Let’s take a look at how they’re written.
     The diagram to the right displays an HTML paragraph element. As we can see, the paragraph element is made up of:

  <ol>
    <li>An opening tag &quot;(&lt;p&gt;)&quot;</li>
    <li>The content (“Hello World!” text)</li>
    <li>A closing tag (&lt;p&gt;)</li>
  </ol> 
    A tag and the content between it is called an HTML element. There are many tags that we can use to organize and display text and other types of content, like images.
  </p>

<p>Let’s quickly review each part of the element pictured:
<ul>
   <li>HTML element (or simply, element) &ndash; a unit of content in an HTML document formed by HTML tags and the text or media it contains.</li>
   <li>HTML Tag - the element name, surrounded by an opening (&lt;) and closing (&gt;) angle bracket.</li>
   <li>Opening Tag - the first HTML tag used to start an HTML element. The tag type is surrounded by opening and closing angle brackets.</li>
   <li>Content - The information (text or other elements) contained between the opening and closing tags of an HTML element.</li>
   <li>Closing tag - the second HTML tag used to end an HTML element. Closing tags have a forward slash (/) inside of them, directly after the left angle bracket.</li>
</ul>
</p>

   <p> I put the rest of notes, review notes in comment tag. Open editor to view </p>

   <p>Let’s review what you’ve learned so far:
   <ol>
     <li>HTML stands for HyperText Markup Language and is used to create the structure and content of a webpage.</li>
     <li>Most HTML elements contain opening and closing tags with raw text or other HTML tags between them.</li>
     <li>HTML elements can be nested inside other elements. The enclosed element is the child of the enclosing parent element.</li>
     <li>Any visible content should be placed within the opening and closing &lt;body&gt; tags.</li>
     <li>Headings and sub-headings, &lt;h1&gt; to &lt;h6&gt; tags, are used to provide titles for sections of content.</li>
     <li>&lt;p&gt;, &lt;span&gt; and &lt;div&gt; tags specify text or blocks.</li>
     <li>The &lt;em&gt; and &lt;strong&gt; tags are used to emphasize text.</li>
     <li>Line breaks are created with the &lt;br&gt; tag.</li>
     <li>Ordered lists (&lt;ol&gt;) are numbered and unordered lists (&lt;ul&gt;) are bulleted.</li>
     <li>Images (&lt;img&gt;) and videos (&lt;video&gt;) can be added by linking to an existing source.</li>
  </ol>      
  </p>

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


<h2>HTML structure</h2> 

<p>Let’s review what you’ve learned this lesson:
  <ol>
     <li>The <!DOCTYPE html> declaration should always be the first line of code in your HTML files. This lets the browser know what version of HTML to expect.</li>
     <li>The &lt;html&gt; element will contain all of your HTML code.</li>
     <li>Information about the web page, like the title, belongs within the <head> of the page.</li>
     <li>You can add a title to your web page by using the <title> element, inside of the head.</li>
     <li>A webpage’s title appears in a browser’s tab.</li>
     <li>Anchor tags (&lt;a&gt;) are used to link to internal pages, external pages or content on the same page.</li>
     <li>You can create sections on a webpage and jump to them using <a> tags and adding ids to the elements you wish to jump to.</li>
     <li>Whitespace between HTML elements helps make code easier to read while not changing how elements appear in the browser.</li>
     <li>Indentation also helps make code easier to read. It makes parent-child relationships visible.</li>
     <li>Comments are written in HTML using the following syntax: &lt;!-- comment --&gt;.</li>
     </ol>
  </p>

<h2>Introduction to Tables</h2>

<p> There are many websites on the Internet that display information like stock prices, sports scores, invoice data, and more. This data is tabular in nature, meaning that a table is often the best way of presenting the data. In this part of the course, we’ll learn how to use the HTML &lt;table&gt; element to present information in a two-dimensional table to the users. </p>

<p> Let’s get started! </p>

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


<p>Great job! In this lesson, we learned how to create a table, add data to it, and section the table into smaller parts that make it easier to read.</p>

<p>Let’s review what we’ve learned so far: 
  <ol>
     <li>The &lt;table&gt; element creates a table.</li>
     <li>The &lt;tr&gt; element adds rows to a table.</li>
     <li>To add data to a row, you can use the &lt;td&lg; element.</li>
     <li>Table headings clarify the meaning of data. Headings are added with the &lt;th&gt; element.</li>
     <li>Table data can span columns using the colspan attribute.</li>
     <li>Table data can span rows using the rowspan attribute.</li>
     <li>Tables can be split into three main sections: a head, a body, and a footer.</li>
     <li>A table’s head is created with the &lt;thead&gt; element.</li>
     <li>A table’s body is created with the &lt;tbody&gt; element.</li>
     <li>A table’s footer is created with the &lt;tfoot&gt; element.</li>
     <li>All the CSS properties you learned about in this course can be applied to tables and their data.</li>
  </ol>
      
   Congratulations on completing HTML Tables!
</p>


```

<!DOCTYPE html>
<html>
  <head>
    <title>Ship To It - Company Packing List</title>
    <link
      href="https://fonts.googleapis.com/css?family=Lato: 100,300,400,700|Luckiest+Guy|Oxygen:300,400"
      rel="stylesheet"
    />
    <link href="style.css" type="text/css" rel="stylesheet" />
  </head>
  <body>
    <ul class="navigation">
      <li>
        <img
          src="https://content.codecademy.com/courses/web-101/unit-9/htmlcss1-img_logo-shiptoit.png"
          height="20px;"
        />
      </li>
      <li class="active">Action List</li>
      <li>Profiles</li>
      <li>Settings</li>
    </ul>

    <div class="search">Search the table</div>

    <table>
      <thead>
        <tr>
          <th scope="col">Company Name</th>
          <th scope="col">Number of Items to Ship</th>
          <th scope="col">Next Action</th>
        </tr>
      </thead>

      <tbody>
        <tr>
          <td>Adam's Greenworks</td>
          <td>14</td>
          <td>Package Items</td>
        </tr>
        <tr>
          <td>Davie's Burgers</td>
          <td>2</td>
          <td>Send Invoice</td>
        </tr>
        <tr>
          <td>Baker's Bike Shop</td>
          <td>3</td>
          <td>Send Invoice</td>
        </tr>
        <tr>
          <td>Miss Sally's Southern</td>
          <td>4</td>
          <td>Ship</td>
        </tr>
        <tr>
          <td>Summit Resort Rentals</td>
          <td>4</td>
          <td>Ship</td>
        </tr>
        <tr>
          <td>Strike Fitness</td>
          <td colspan="2">1</td>
          <td>Enter Order</td>
        </tr>
      </tbody>
      <tfoot>
        <td>Total</td>
        <td>28</td>
      </tfoot>
    </table>
  </body>
</html>


```

> Text that is a quote






<h2>Introduction to HTML Forms</h2>

<p>Forms are a part of everyday life. When we use a physical form in real life, we write down information and give it to someone to process. Think of the times you’ve had to fill out information for various applications like a job, or a bank account, or dropped off a completed suggestion card — each instance is a form!

Just like a physical form, an HTML &lt;form&gt; element is responsible for collecting information to send somewhere else. Every time we browse the internet we come into contact with many forms and we might not even realize it. There’s a good chance that if you’re typing into a text field or providing an input, the field that you’re typing into is part of a &lt;form&lt;!

In this lesson, we’ll go over the structure and syntax of a &lt;form&gt; and the many elements that populate it.</p>

<p>
Nice work interacting with the extremely common and useful <form> element!

In this lesson we went over:
<ul>
<li>The purpose of a &lt;form&gt; is to allow users to input information and send it.</li>
<li>The &lt;form&gt;‘s action attribute determines where the form’s information goes.</li>
<li>The &lt;form&gt;‘s method attribute determines how the information is sent and processed.</li>
      <ul>
        <li>To add fields for users to input information we use the &lt;input&gt; element and set the type attribute to a field of our choosing:</li>
        <li>Setting type to "text" creates a single row field for text input.</li>
        <li>Setting type to "password" creates a single row field that censors text input.</li>
        <li>Setting type to "number" creates a single row field for number input.</li>
        <li>Setting type to "range" creates a slider to select from a range of numbers.</li>
        <li>Setting type to "checkbox" creates a single checkbox that can be paired with other checkboxes.</li>
        <li>Setting type to "radio" creates a radio button that can be paired with other radio buttons.</li>
        <li>Setting type to "text" and adding the list attribute will pair the &lt;input&gt; with a &lt;datalist&gt; element if the list of &lt;input&gt; and the id of <datalist> are the same.</li>
        <li>Setting type to "submit" creates a submit button.</li>
      </ul>      
<li>A &lt;select&gt; element is populated with &lt;option&gt; elements and renders a dropdown list selection.</li>
<li>A &lt;datalist&gt; element is populated with &lt;option&gt; elements and works with an &lt;input&gt; to search through choices.</li>
<li>A &lt;textarea&gt; element is a text input field that has a customizable area.</li>
<li>When a &lt;form&gt; is submitted, the name of the fields that accept input and the value of those fields are sent as name=value pairs.</li>
<li>Using the &lt;form&gt; element in conjunction with the other elements listed above allows us to create sites that take into consideration the wants and needs of our users. Take the opportunity to take what you’ve learned, and apply it!</li>
</ul>
</p>




<h2>Introduction to HTML Form Validation</h2>
<p>
Ever wonder how a login page actually works? Or why the combination of a username and password grants you access to a website? The answers lie in validation. Validation is the concept of checking user provided data against the required data.

There are different types of validation. One type is server-side validation, this happens when data is sent to another machine (typically a server) for validation. An example of this type of validation is the usage of a login page. The form on the login page accepts username and password input, then sends the data to a server that checks that the pair matches up correctly.

On the other hand, we use client-side validation if we want to check the data on the browser (the client). This validation occurs before data is sent to the server. Different browsers implement client-side validation differently, but it leads to the same outcome.

Shared among the different browsers are the benefits of using HTML5’s built-in client-side validation. It saves us time from having to send information to the server and wait for the server to send back confirmation or rejection of the data. This can also help us protect our server from malicious code or data from a malicious user. It also allows us to quickly give feedback to users for specific fields rather than having them fill in a form again if the data they input into the form was rejected.

In this lesson, we’ll learn how to add some validation checks to our &lt;form&gt;s!
</p>


<p>Awesome job adding client-side validation to &lt;form&gt;s!

Let’s quickly recap:
<ul>
   <li>Client-side validations happen in the browser before information is sent to a server.</li>
   <li>Adding the required attribute to an input related element will validate that the input field has information in it.</li>
   <li>Assigning a value to the min attribute of a number input element will validate an acceptable minimum value.</li>
   <li>Assigning a value to the max attribute of a number input element will validate an acceptable maximum value.</li>
   <li>Assigning a value to the minlength attribute of a text input element will validate an acceptable minimum number of characters.</li>
   <li>Assigning a value to the maxlength attribute of a text input element will validate an acceptable maximum number of characters.</li>
   <li>Assigning a regex to pattern matches the input to the provided regex.</li>
   <li>If validations on a &lt;form&gt; do not pass, the user gets a message explaining why and the &lt;form&gt; cannot be submitted.</li>
</ul>
    These quick checks help ensure that input data is correct and safe for our servers. It also helps give users immediate feedback on what they need to fix instead of having to wait for a server to send back that information.


</p>




<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
</picture>

</body>


