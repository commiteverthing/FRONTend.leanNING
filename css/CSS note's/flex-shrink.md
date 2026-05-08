CSS flex-shrink Property

Example
Let the second flex-item shrink three times more than the rest:

div:nth-of-type(2) {
  flex-shrink: 3;
}
Definition and Usage
The flex-shrink property specifies how the item will shrink relative to the rest of the flexible items inside the same container.

Note: If the element is not a flexible item, the flex-shrink property has no effect.

Default value:	1
Inherited:	no
Animatable:	yes. Read about animatable
Version:	CSS3
JavaScript syntax:	object.style.flexShrink="5"
Browser Support
The numbers in the table specify the first browser version that fully supports the property.

Property					
flex-shrink	29	11	28	9	17

CSS Syntax
flex-shrink: number|initial|inherit;
Property Values
Value	Description	Play it
number	A number specifying how much the item will shrink relative to the rest of the flexible items. Default value is 1	
initial	Sets this property to its default value. Read about initial	
inherit	Inherits this property from its parent element. Read about inherit