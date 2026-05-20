CSS Box Shadow
CSS box-shadow Property
The CSS box-shadow property is used to apply one or more shadows to an element.

Norway
Box shadow

In its simplest use, you can only specify the horizontal and the vertical offset of the shadow.

In addition, you can add a shadow color, a spread radius, a blur effect, and change the shadow from an outer shadow to an inner shadow (inset).

CSS Horizontal and Vertical Shadow
In its simplest use, you only specify the horizontal and the vertical offset of the shadow.

The default color of the shadow is the current text color.

A <div> element with a box-shadow
Example
Specify a horizontal and a vertical shadow:

div {
  box-shadow: 10px 10px;
}
Specify a Color for the Shadow
The color parameter defines the color of the shadow.

A <div> element with a lightblue box-shadow
Example
Specify a color for the shadow:

div {
  box-shadow: 10px 10px lightblue;
}

Add a Blur Effect to the Shadow
The blur parameter defines the blur radius of the shadow. The higher the number, the more blurred the shadow will be.

A <div> element with a 5px blurred, lightblue box-shadow
Example
Add a blur effect to the shadow:

div {
  box-shadow: 10px 10px 5px lightblue;
}
Set the Spread Radius of the Shadow
The spread parameter defines the spread radius of the shadow.

A positive value increases the size of the shadow, and a negative value decreases the size of the shadow.

A <div> element with a blurred, lightblue box-shadow, with a spread radius of 12px
Example
Set the spread radius of the shadow:

div {
  box-shadow: 10px 10px 5px 12px lightblue;
}
Set the inset Parameter
The inset parameter changes the shadow from an outer shadow (outset) to an inner shadow (inside an element's frame).

A <div> element with a blurred, lightblue, inset box-shadow
Example
Add the inset parameter:

div {
  box-shadow: 10px 10px 5px lightblue inset;
}
Add Multiple Shadows
An element can also have multiple shadows.

To attach more than one shadow to an element, add a comma-separated list of shadows.

A <div> element with multiple shadows
Example
div {
  box-shadow: 5px 5px 8px blue, 10px 10px 8px red, 15px 15px 8px green;
}
Creating Shadow Cards
You can also use the box-shadow property to create paper-like cards:

1
January 1, 2021

Norway
Hardanger, Norway

Example
div.card {
  width: 250px;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
  text-align: center;
}
 
