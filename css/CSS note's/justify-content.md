# 📘 CSS Notes: justify-content

## 🔹 Definition

`justify-content` is a CSS property used in **Flexbox** (and Grid) to control how items are spaced **along the main axis**.

👉 It works in **one direction only (main axis)**.

---

## 🔹 Main Axis (Very Important)

When you use:

```css
.container {
  display: flex;
}
```

Default direction:

```css
flex-direction: row;
```

👉 This means:

* Main axis = **horizontal (left → right)**

So:

👉 `justify-content` controls **horizontal spacing**

---

## 🔹 Concept

Think of a container like this:

```
|                |
```

With items inside:

```
| A  B  C       |
```

👉 `justify-content` decides:
**Where items (A, B, C) should be placed inside the container**

---

## 🔹 Values

### 1. flex-start

```css
justify-content: flex-start;
```

👉 Items align to the **left (start)**

```
| A B C         |
```

---

### 2. flex-end

```css
justify-content: flex-end;
```

👉 Items align to the **right (end)**

```
|         A B C |
```

---

### 3. center

```css
justify-content: center;
```

👉 Items align to the **center**

```
|    A B C      |
```

---

### 4. space-between

```css
justify-content: space-between;
```

👉 First item → left
👉 Last item → right
👉 Equal space between items

```
| A     B     C |
```

---

### 5. space-around

```css
justify-content: space-around;
```

👉 Equal space around each item
👉 Edge spaces are smaller

```
|  A   B   C  |
```

---

### 6. space-evenly

```css
justify-content: space-evenly;
```

👉 Equal spacing everywhere (best symmetry)

```
|   A   B   C   |
```

---

## 🔹 Important Notes

* Works only when:

```css
display: flex;
```

* Direction depends on `flex-direction`:

  * `row` → horizontal
  * `column` → vertical

---

## 🔥 Final Summary

👉 `justify-content`
= **Controls how items are distributed along the main axis (horizontal by default)**

---
