Multiple Style Sheets & Cascading Order
Multiple Style Sheets

If some properties have been defined for the same selector (element) in different style sheets, the value from the last read style sheet will be used. 

Assume that an external style sheet has the following style for the <h1> element:
h1 {
  color: navy;
}

Then, assume that an internal style sheet also has the following style for the <h1> element:
h1 {
  color: orange;   
}
Example

If the internal style is defined after the link to the external style sheet, the <h1> elements will be "orange":
<head>
<link rel="stylesheet" type="text/css" href="mystyle.css">
<style>
h1 {
  color: orange;
}
</style>
</head>
Example

However, if the internal style is defined before the link to the external style sheet, the <h1> elements will be "navy": 
<head>
<style>
h1 {
  color: orange;
}
</style>
<link rel="stylesheet" type="text/css" href="mystyle.css">
</head>
Cascading Order

What style will be used when there is more than one style specified for an HTML element?

All the styles in a page will "cascade" into a new "virtual" style sheet by the following rules, where number one has the highest priority:

    Inline style (inside an HTML element)
    External and internal style sheets (in the head section)
    Browser default

So, an inline style has the highest priority, and will override external and internal styles and browser defaults.