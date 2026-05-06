CSS flex-wrap Property

Example

Make the flexible items wrap if necessary:
div {
  display: flex;  
  flex-wrap: wrap;
}
Definition and Usage

The flex-wrap property specifies whether the flexible items should wrap or not.

Note: If the elements are not flexible items, the flex-wrap property has no effect.

Default value: 	nowrap
Inherited: 	no
Animatable: 	no. Read about animatable
Version: 	CSS3
JavaScript syntax: 	object.style.flexWrap="nowrap"
Browser Support

The numbers in the table specify the first browser version that fully supports the property.
Property 					
flex-wrap 	29 	11 	28 	9 	17
CSS Syntax
flex-wrap: nowrap|wrap|wrap-reverse|initial|inherit;
Property Values
Value 	Description 	Play it
nowrap 	Default value. Specifies that the flexible items will not wrap 	
wrap 	Specifies that the flexible items will wrap if necessary 	
wrap-reverse 	Specifies that the flexible items will wrap, if necessary, in reverse order 	
initial 	Sets this property to its default value. Read about initial 	
inherit 	Inherits this property from its parent element. Read about inherit