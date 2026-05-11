# Media Queries in CSS

## Introduction
Media Queries are used in CSS to make websites **responsive**.  
They allow the website layout and styles to change depending on:

- Screen size
- Device width
- Device height
- Orientation
- Resolution

Media Queries help websites look good on:

- Mobile phones
- Tablets
- Laptops
- Desktop screens

---

# Basic Syntax

```css
@media (condition) {
    selector {
        property: value;
    }
}
```

---

# Example 1: Change Background Color

```css
body{
    background-color: lightblue;
}

@media (max-width: 600px){
    body{
        background-color: lightgreen;
    }
}
```

## Explanation
- If the screen width becomes **600px or smaller**
- The background color changes to **lightgreen**

---

# Common Media Query Conditions

| Condition | Meaning |
|---|---|
| `max-width` | Applies styles below a specific width |
| `min-width` | Applies styles above a specific width |
| `orientation: portrait` | Mobile vertical mode |
| `orientation: landscape` | Horizontal mode |

---

# Example 2: Responsive Text

```css
h1{
    font-size: 40px;
}

@media (max-width: 768px){
    h1{
        font-size: 25px;
    }
}
```

## Explanation
- Large screens → `40px`
- Smaller screens → `25px`

---

# Example 3: Mobile Navigation

```css
.navbar{
    display: flex;
    gap: 20px;
}

@media (max-width: 700px){
    .navbar{
        flex-direction: column;
    }
}
```

## Explanation
- Desktop → Navbar items in row
- Mobile → Navbar items in column

---

# Most Common Breakpoints

| Device | Width |
|---|---|
| Mobile | `0px - 600px` |
| Tablet | `601px - 768px` |
| Laptop | `769px - 1024px` |
| Desktop | `1025px+` |

---

# Responsive Design Example

```css
.container{
    display: flex;
    gap: 20px;
}

.box{
    width: 300px;
    height: 200px;
    background-color: orange;
}

/* Mobile */
@media (max-width: 600px){
    .container{
        flex-direction: column;
    }

    .box{
        width: 100%;
    }
}
```

---

# Important Notes

## 1. Mobile First Approach

Best practice:

```css
/* Mobile styles first */

.box{
    width: 100%;
}

/* Larger screens */

@media (min-width: 768px){
    .box{
        width: 50%;
    }
}
```

---

## 2. `max-width` vs `min-width`

### `max-width`
Used for:
- Desktop → Mobile

```css
@media (max-width: 600px)
```

Means:
- Apply styles below `600px`

---

### `min-width`
Used for:
- Mobile → Desktop

```css
@media (min-width: 600px)
```

Means:
- Apply styles above `600px`

---

# Real World Usage

Media Queries are used for:

- Responsive websites
- Mobile navigation
- Responsive grids
- Responsive images
- Changing font sizes
- Flexbox layouts
- Hiding/showing elements

---

# Example: Hide Element on Mobile

```css
@media (max-width: 600px){
    .sidebar{
        display: none;
    }
}
```

---

# Combining Conditions

```css
@media (min-width: 600px) and (max-width: 900px){
    body{
        background-color: pink;
    }
}
```

## Explanation
- Styles apply only between:
  - `600px`
  - `900px`

---

# Why Media Queries Are Important

Without Media Queries:
- Website may break on small screens
- Text can become too large
- Layout may overflow

With Media Queries:
- Better user experience
- Responsive design
- Mobile friendly websites

---

# Summary

- Media Queries make websites responsive
- They apply CSS based on screen size
- `max-width` → below width
- `min-width` → above width
- Mostly used with Flexbox and Grid

---

# Quick Example

```css
@media (max-width: 768px){
    .container{
        flex-direction: column;
    }
}
```

This means:
- When screen becomes smaller than `768px`
- Items move from row → column



------- MORE MEDIA QUERY -----------

CSS Media Queries
CSS Media Queries
CSS media queries allow you to apply styles based on the characteristics of a device or the environment displaying the web page.

CSS media queries are essential for creating responsive web pages.

The CSS @media rule is used to add media queries to your style sheet.

Media Query Syntax
A media query consists of an optional media-type and one or more media-features, which resolve to either true or false.

@media [not] media-type and (media-feature: value) and (media-feature: value) {
  /* CSS rules to apply */
}
The media-type is optional. However, if you use not, you must also specify a media-type.

The result of a media query is true if the specified media-type matches the type of device, and all media-features are true. When a media query is true, the corresponding style rules are applied, following the normal cascading rules.

Meaning of the not and and keywords:

not: This optional keyword inverts the meaning of the entire media query.

and: This keyword combines a media-type and one or more media-features.

CSS Media Types
The optional media type specifies the type of media the styles are for. If media type is omitted, it will be set to "all".

Value	Description
all	Used for all media type devices
print	Used for print preview mode
screen	Used for computer screens, tablets, and smart-phones

CSS Media Features
The media feature specifies a specific characteristic of the device.

Here are some commonly used media features:

Value	Description
max-height	Maximum height of the viewport
min-height	Minimum height of the viewport
height	Height of the viewport (including scrollbar)
max-width	Maximum width of the viewport
min-width	Minimum width of the viewport
width	Width of the viewport (including scrollbar)
orientation	Orientation of the viewport (landscape or portrait)
resolution	Screen resolution
prefers-color-scheme	User's preferred color scheme (light or dark)
Media Queries Examples
Here, we use a media query to change the background-color of the body to lightgreen, if the width of the viewport is 480px, or wider:

Example
@media screen and (min-width: 480px) {
  body {
    background-color: lightgreen;
  }
}
Here, we use a media query to change the background-color of the body to lightgreen, if the width of the viewport is between 480px and 768px:

Example
@media screen and (min-width: 480px) and (max-width: 768px) {
  body {
    background-color: lightgreen;
  }
}
