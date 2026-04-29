CSS Font Style
CSS Font Style

The CSS font-style property specifies the font style for a text..

This property can have one of the following values:

    normal - The text is shown normally
    italic - The text is shown in italics
    oblique - The text is "leaning" (oblique is very similar to italic)

Example
p.normal {
  font-style: normal;
}

p.italic {
  font-style: italic;
}

p.oblique {
  font-style: oblique;
}
CSS Font Weight

The CSS font-weight property specifies how thick or thin characters in text should be displayed.

This property can have one of the following values:

    normal - This is default. Defines normal characters
    bold - Defines thick characters
    bolder - Defines thicker characters
    lighter - Defines lighter characters
    100-900 - Defines from thin to thick characters. 400 is the same as normal, and 700 is the same as bold

Example
p.normal {
  font-weight: normal;
}

p.light {
  font-weight: lighter;
}

p.thick {
  font-weight: bold;
}

p.thicker {
  font-weight: 900;
}
CSS Font Variant

The CSS font-variant property specifies whether or not a text should be displayed in a small-caps font.

In a small-caps font, all lowercase letters are converted to uppercase letters. However, the converted uppercase letters appears in a smaller font size than the original uppercase letters in the text.
Example
p.normal {
  font-variant: normal;
}

p.small {
  font-variant: small-caps;
} 