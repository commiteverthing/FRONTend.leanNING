CSS Margins


The CSS margin properties are used to create space around elements, outside of any defined borders.

Margins define the distance between an element's border and the surrounding elements.

With CSS, you have full control over the margins. CSS has properties for setting the margin for each individual side of an element (top, right, bottom, and left), and a shorthand property for setting all the margin properties in one declaration.
This element has a margin of 70px.
Margin - Individual Sides

CSS has properties for specifying the margin for each side of an element:

    margin-top - sets the top margin of an element
    margin-right - sets the right margin of an element
    margin-bottom - sets the bottom margin of an element
    margin-left - sets the left margin of an element

All the margin properties can have the following values:

    auto - the browser calculates the margin
    length - specifies a margin in px, pt, cm, etc.
    % - specifies a margin in % of the width of the containing element
    inherit - specifies that the margin should be inherited from the parent element

Tip: Negative values are also allowed.
Example

Set different margins for all four sides of a <p> element:
p {
  margin-top: 100px;
  margin-bottom: 100px;
  margin-right: 150px;
  margin-left: 80px;
}
Margin - Shorthand Property

To shorten the code, it is possible to specify all the margin properties in one declaration.

The margin property is a shorthand property for the following individual margin properties:

    margin-top
    margin-right
    margin-bottom
    margin-left

Here is how it works:

If the margin property has four values:

    margin: 25px 50px 75px 100px;
        top margin is 25px
        right margin is 50px
        bottom margin is 75px
        left margin is 100px

Example

Use the margin shorthand property with four values:
p {
  margin: 25px 50px 75px 100px;
}

If the margin property has three values:

    margin: 25px 50px 75px;
        top margin is 25px
        right and left margins are 50px
        bottom margin is 75px

Example

Use the margin shorthand property with three values: 
p {
  margin: 25px 50px 75px;
}

If the margin property has two values:

    margin: 25px 50px;
        top and bottom margins are 25px
        right and left margins are 50px

Example

Use the margin shorthand property with two values: 
p {
  margin: 25px 50px;
}

If the margin property has one value:

    margin: 25px;
        all four margins are 25px

Example

Use the margin shorthand property with one value: 
p {
  margin: 25px;
}
The auto Value

You can set the margin property to auto to horizontally center the element within its container.

The element will then take up the specified width, and the remaining space will be split equally between the left and right margins.
Example

Use margin: auto:
div {
  width: 300px;
  margin: auto;
  border: 1px solid red;
}
The inherit Value

You can set the margin property to inherit to let the margin be inherited from the parent element.

This example lets the left margin of the <p class="ex1"> element be inherited from the parent element (<div>):
Example

Use of the inherit value:
div {
  border: 1px solid red;
  margin-left: 100px;
}

p.ex1 {
  margin-left: inherit;
}
Exercise?
Drag and drop the correct values to set the margins:
10px for top, 20px for right, 30px for bottom, and 40px for left.
div {
  width: 200px;
  margin: 10px 20px 30px 40px;
}


All CSS Margin Properties
Property 	Description
margin 	A shorthand property for setting all the margin properties in one declaration
margin-bottom 	Sets the bottom margin of an element
margin-left 	Sets the left margin of an element
margin-right 	Sets the right margin of an element
margin-top 	Sets the top margin of an element