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

CONTENT STRUCTURING

1. Main
The main element is used once per webpage and tells the browser where the main content is located.

2. Header
The header and footer elements mark the header and footer areas on the page. Do not confuse header with head though. Head is where the file's metadata lives and is not displayed to users. Header is used for site headers, article headers, and headers within the content. A header is usually found at the top of most web pages and may include a logo, site name, and navigation.

3. Footer
The footer signifies that there are extra things to convey, regardless of its position on the page.

4. Article
An article often starts with a title, subtitle, author's name, and publication date, which can also be considered a header. Many web pages end with a footer at the bottom, containing links, copyright information, and additional details about the company. However, footers can also appear elsewhere. Some articles begin with metadata like hashtags or share buttons, which are suitable for a footer element. The article element wraps around any type of content unit, whether it is a long written article, a short snippet, a teaser card, a tweet, or even an app element. It represents a standalone unit of content.

5. Section
The section element is used to mark sections of content. For example, in a long essay with subheadings, each segment can be wrapped in a section element. It is also useful for dividing different topic zones on a website. Each section typically starts with its own headline.

6. Aside
Lastly, the aside element is for content that is off to the side, like sidebar information or additional details that accompany an article but are not part of its main flow. Advertisements can also be marked as an aside. Although the position on the page does not matter, the semantic meaning of these elements is crucial. The visual layout often conveys meaning, and these HTML elements help transfer that meaning from the design to the content.

Building Html table:

 HTML table. The table element wraps around the whole table, around all our content and markup for that table, marking the beginning and end of the table itself. The TR element stands for table row and wraps around a set of elements, defining them as belonging to the same row. The TH element stands for table header and defines a header for a column. The TD element stands for table data and marks up the cells of data. 


<table>wraps the whole table</table>
<tr>wraps around the set of elements,defining them as belonging to the same row</tr>
<th>defines a header for a column</th>
<td>Marks the actual bits of data</td>






 
