What is CSS?

CSS is the language we use to style a Web page.

    CSS stands for Cascading Style Sheets
    CSS describes how HTML elements are to be displayed on screen, paper, or in other media
    CSS saves a lot of work. It can control the layout of multiple web pages all at once
    External stylesheets are stored in CSS files

CSS Demo - One HTML Page - Multiple Styles!


CSS Syntax

A CSS rule consists of a selector and a declaration block:

CSS selector

The selector points to the HTML element you want to style.

The declaration block contains one or more declarations separated by semicolons.

Each declaration includes a CSS property name and a value, separated by a colon.

Multiple CSS declarations are separated with semicolons, and declaration blocks are surrounded by curly braces.
Example

In this example all <p> elements will be center-aligned, with a red text color:


p {
  color: red;
  text-align: center;
} 

Example Explained

    p is a selector in CSS (it points to the HTML element you want to style: <p>).
    color is a property, and red is the property value
    text-align is a property, and center is the property value
