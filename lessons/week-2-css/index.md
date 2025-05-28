# 🎨 Week 2 – CSS Basics

Welcome to **Week 2** of the EthioHope Kids Bootcamp! This week, we are diving into the fun world of **CSS (Cascading Style Sheets)** — the magical tool that makes your website look beautiful!

---

## 🧠 What is CSS?

CSS stands for **Cascading Style Sheets**. It is a language used to **style** the HTML content on your web page.

With CSS, you can:

- Change colors
- Resize text
- Add backgrounds
- Move things around
- Make things look modern and fun!

HTML is for structure. CSS is for style.

---

## 🧰 Three Ways to Add CSS

1. ### Inline Style (inside the HTML tag)

```html
<p style="color: red;">This is red text!</p>
```

2. ### Internal Style (inside a `<style>` tag in your HTML head)

```html
<head>
  <style>
    h1 {
      color: blue;
    }
  </style>
</head>
```

3. ### External Style (linked CSS file like `style.css`)

```html
<head>
  <link rel="stylesheet" href="style.css" />
</head>
```

This is the best way for bigger projects!

---

## 🏷️ CSS Syntax

```css
selector {
  property: value;
}
```

Example:

```css
p {
  color: green;
  font-size: 18px;
}
```

---

## 🎯 Selectors in CSS

- **Tag Selector:** Targets all tags like `p`, `h1`, `img`

```css
h1 {
  color: purple;
}
```

- **Class Selector:** Use when you want to style many things the same way

```html
<div class="card"></div>
```

```css
.card {
  background-color: yellow;
}
```

- **ID Selector:** Use when you're styling one specific thing

```html
<p id="welcome"></p>
```

```css
#welcome {
  font-weight: bold;
}
```

---

## 🎨 Common CSS Properties

| Property           | What It Does                 |
| ------------------ | ---------------------------- |
| `color`            | Text color                   |
| `background-color` | Background color             |
| `font-size`        | Size of the text             |
| `font-family`      | Style of the font            |
| `text-align`       | Align text left/center/right |
| `padding`          | Space inside the box         |
| `margin`           | Space outside the box        |
| `border`           | Adds borders around elements |
| `width` / `height` | Size of the element          |

---

## 👩‍💻 Fun Fact!

You can even make animations and cool effects with CSS later on!

---

Now that we know the basics, let’s go build our **Colorful Info Card**! 🎨
