CSS @font-face Rule



Example

Specify a font named "myFirstFont", and specify the URL where it can be found:
@font-face {
  font-family: myFirstFont;
  src: url(sansation_light.woff);
}

More "Try it Yourself" examples below.
Definition and Usage

With the CSS @font-face rule, web designers do not have to use one of the "web-safe" fonts anymore.

In the @font-face rule you must first define a name for the font (e.g. myFirstFont), and then point to the font file.

To use the font for an HTML element, refer to the name of the font (myFirstFont) through the font-family property:
div {
  font-family: myFirstFont;
}
Browser Support

The @font-face rule is supported in Edge, Chrome, Firefox, Safari, and Ope