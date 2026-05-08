CSS align-items Property

Example
Center the alignments for all the items of the flexible <div> element:

div {
  display: flex;
  align-items: center;
}
More "Try it Yourself" examples below.

Definition and Usage
The align-items property specifies the default alignment for items inside a flexbox or grid container.

In a flexbox container, the flexbox items are aligned on the cross axis, which is vertical by default (opposite of flex-direction).
In a grid container, the grid items are aligned in the block direction. For pages in English, block direction is downward and inline direction is left to right.
For this property to have any alignment effect, the items need available space around themselves in the appropriate direction.

Tip: Use the align-self property of each item to override the align-items property.


Default value:	normal
Inherited:	no
Animatable:	no. Read about animatable
Version:	CSS3
JavaScript syntax:	object.style.alignItems="center"
Browser Support
The numbers in the table specify the first browser version that fully supports the property.

Property					
align-items	57.0	16.0	52.0	10.1	44.0
REMOVE ADS

CSS Syntax
align-items: normal|stretch|positional alignment|flex-start|flex-end|baseline|initial|inherit;
Property Values
Value	Description	Play it
normal	Default. Behaves like 'stretch' for flexbox and grid items, or 'start' for grid items with a defined block size.	
stretch	Items are stretched to fit the container	
center	Items are positioned at the center of the container	
flex-start	Items are positioned at the beginning of the container	
flex-end	Items are positioned at the end of the container	
start	Items are positioned at the beginning of their individual grid cells, in the block direction	
end	Items are positioned at the end of the their individual grid cells, in the block direction	
baseline	Items are positioned at the baseline of the container	
initial	Sets this property to its default value. Read about initial	
inherit	Inherits this property from its parent element. Read about inherit	
More Examples
Example
Items are positioned at the beginning of the container:

div {
  display: flex;
  align-items: flex-start;
}
Example
Items are positioned at the end of the container:

div {
  display: flex;
  align-items: flex-end;
}
Example
Items are positioned at the baseline of the container:

div {
  display: flex;
  align-items: baseline;
}
Example
Items are stretched to fit the container:

div {
  display: flex;
  align-items: stretch;
}
Example with grid
Items are aligned at the start of each grid cell in the block direction:

#container {
  display: grid;
  align-items: start;
}
Example with absolute positioning
Items are aligned at the end of each grid cell in the block direction for absolute positioned grid items:

#container {
  display: grid;
  position: relative;
  align-items: end;
}

#container > div {
  position: absolute;
}
 