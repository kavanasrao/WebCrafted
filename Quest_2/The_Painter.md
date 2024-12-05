**Quest 2 :** *CSS ~ The Painter of the Web*

# What is CSS ? 
CSS (Cascading Style Sheets) is a stylesheet language used to describe the presentation and design of a document written in HTML or XML. While HTML structures the content of a webpage, CSS controls the layout, colors, fonts, and other visual aspects, making websites look attractive and easy to navigate.

# Why is CSS Needed ?
CSS is crucial for the following reasons:
<ul>
    <li>
        Separation of Content and Style: CSS allows you to separate the structure (HTML) and the visual style (CSS), making it easier to manage and update the design without affecting the content.
    </li>
    <li>
        Customization: CSS gives you full control over the look and feel of your website. You can set colors, fonts, margins, and layouts, creating a unique visual style.
    </li>
    <li>
        Responsive Design: With CSS, you can design websites that adjust to different screen sizes (mobile, tablet, desktop), ensuring an optimal experience for all users.
    </li>
    <li>
        Consistency: CSS enables you to apply consistent styles across multiple pages, ensuring uniformity in design throughout the website.
    </li>
</ul>

# How Does CSS Work ?

CSS works by applying styles to HTML elements based on selectors. A selector targets an HTML element, and the corresponding declarations specify how the element should appear (such as its color, size, position, etc.). Here's how CSS applies to an HTML page:
- Select HTML Elements: CSS uses selectors to target specific HTML elements, classes, or IDs.
- Define Styles: Declarations are written within curly braces {} to define the styles, such as colors, fonts, and layout properties.
- Apply Styles: Once styles are defined, they are applied to the targeted HTML elements, making the page visually appealing.


<p>
    p{
         { color: blue; font-size: 16px; }
    }
</p>

p {
  color: blue;
  font-size: 16px;
}
***************************************************************
''' html
<!DOCTYPE html>
<html>
  <head>
    <style>
      body {
        background-color: lightgray;
      }
      h1 {
        color: blue;
      }
      p {
        font-size: 18px;
      }
    </style>
  </head>
  <body>
    <h1>Welcome to My Website</h1>
    <p>This is a paragraph styled with CSS.</p>
  </body>
</html>

