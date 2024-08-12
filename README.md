# HTML-CSS
Introduction to HTML 

HTML is used in websites, apps and various software whenever technology is involved, it is basically allowing us to structure our content and bridge the gap between humans and computer languages. 

HTML Syntax  

<p> it is the opening tag 

</p> it is the closing tag 

There is content which is HTML element and is written between opening tag and closing tag. Example <p> HELLO WORLD </p> 

HTML HEADLINES 

The are six levels of headlines; 1st level <h1> content </h1> 

                                                                  2nd level <h2> content </h2> 

                                                                  3rd level <h3> content</h3> 

                                                                   4th level <h4> content </h4> 

                                                                   5th level <h5> content</h5> 

                                                                    6th level <h6> content</h6> 

h1 is Bigger than h2 and h2 is bigger than h3 and this order, h1 serves as the main title and h2 is a subtitle for the content. 

 We use the "<i>" element to apply visual italics and the "<em>" element to add emphasis and elements to make something bold in HTML we use <strong> or <b> 

In conclusion there are four elements in HTML that marks words as bold or italic, and these two (<em> , <strong>) convey meaning and serve a language related purpose. 

And the other two (<i>, <b>) do not have a specific meaning instead they are used for visual styling. 

HTML LISTS 

<ul> is unordered list </ul>, unordered like ingrediants 

<li>flour</li> 

<li>Sunger</li> 

<ol> ordered list </ol>  

<li>in a bowl mix all the dry ingredients</li> 

<li>add sugar and oil</li> 

<li>wait for 5minutes</li> 

The example of a code for ol and ul 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lists</title>
</head>
<body>
    <h1>Lists</h1>
    <h2>Order List</h2>
    <ol>
        <li>First item</li>
        <li>second item</li>
        <li>Third item</li>
    </ol>
    <h2>Unordered list</h2>
    <ul>
        <li>First item</li>
        <li>Second item</li>
        <li>Third item</li>
    </ul>
</body>
</html>

#Links
Create hyperlinks using the <a> tag:
<a href="https://www.example.com">Visit Example.com</a>
href attribute specifies the URL of the page the link goes to.

#images
Add images with the <img> tag:
<img src="image.jpg" alt="Description of image">
src attribute specifies the path to the image file.
alt attribute provides alternative text for accessibility.

HTML navigation and linking are essential for creating an interactive and user-friendly website. They enable users to move between different pages or sections within a webpage:
1. Navigation Menus
Structure: Navigation menus are often created using lists (<ul> or <ol>) and links (<a> tags).
Purpose: They provide a structured way for users to access different sections or pages of a website.
Example:
<nav>
    <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="services.html">Services</a></li>
        <li><a href="contact.html">Contact</a></li>
    </ul>
</nav>

2. Linking to Other Pages
Internal Links: Use the <a> tag to link to other pages within the same website using relative paths.
Example:
<a href="about.html">Learn more about us</a>

External Links
Usage: To link to external websites, include the full URL in the href attribute.
Target Attribute: Adding target="_blank" opens the link in a new tab.
Example:
<a href="https://www.example.com" target="_blank">Visit Example.com</a>

 Breadcrumb Navigation
Purpose: Breadcrumbs provide a trail for users to navigate back to previous sections or pages within a website.
Structure: Usually implemented as an ordered list (<ol>) within a <nav> element.
Example:
<nav aria-label="breadcrumb">
  <ol class="breadcrumb">
    <li class="breadcrumb-item"><a href="index.html">Home</a></li>
    <li class="breadcrumb-item"><a href="category.html">Category</a></li>
    <li class="breadcrumb-item active" aria-current="page">Current Page</li>
  </ol>
</n>




 
