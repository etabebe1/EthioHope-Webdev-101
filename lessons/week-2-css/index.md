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

## 🏏 CSS Syntax

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

## 🐼 Project: My Favorite Animal

Now that you know the basics of CSS, let's build a fun little project called **My Favorite Animal**.

You will:

- Use HTML to structure your content
- Use CSS to style it beautifully
- Add images, lists, and a clickable button

📁 Your files:

- `index.html` → contains the structure of the animal card
- `style.css` → adds color, layout, fonts, and animations
- `panda.jpeg` → the image you use (make sure it's in the same folder!)

🎨 **Colors and Styles Used in CSS**:

- Background color: `#000` (black)
- Card background: `#ffffff` (white)
- Border: `3px dashed #55efc4`
- Font: `'Courier New', Courier, monospace`
- Highlight color: `#55efc4`, `#4ebd92`, `#3a3dcf`
- Hover color: `#4a4cd4`

🔗 **Link in Button**:

- URL: [https://kids.nationalgeographic.com/animals/mammals/facts/giant-panda](https://kids.nationalgeographic.com/animals/mammals/facts/giant-panda)

🎉 Final Result:

A bright and fun profile card that shows off your favorite animal — Panda! Kids will love it!

---

Next up? In **Week 3**, we’ll begin working with positioning, layout, and real-world mini websites!

Happy coding, young devs! 💻🌟
