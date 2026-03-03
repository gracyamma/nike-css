

---

# 🖼️ Tailwind CSS Grid Gallery

A simple responsive image grid built using **HTML** and **Tailwind CSS (CDN version)**.
This layout demonstrates how to use Tailwind’s `grid`, `col-span`, `row-span`, and `aspect-square` utilities to create a modern gallery design.

---

## 🚀 Features

* 4-column CSS Grid layout
* Responsive spacing using Tailwind utilities
* Square aspect ratio images (`aspect-square`)
* Featured images spanning multiple rows and columns
* Simple motivational tagline inside the grid
* Uses Tailwind CSS via CDN (no build setup required)

![image](./photo%20gallery.png)
---

## 📂 Project Structure

```
project-folder/
│
├── index.html
└── README.md
```

---

## 🛠️ Technologies Used

* HTML5
* Tailwind CSS (via CDN)

```html
<script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
```

---

## 📸 Layout Explanation

### Grid Container

```html
<div class="container bg-blue-300 p-2 w-1/2 grid gap-1 grid-cols-4">
```

* `grid` → Enables CSS Grid
* `grid-cols-4` → Creates 4 equal columns
* `gap-1` → Adds spacing between items
* `w-1/2` → Sets container width to 50%
* `p-2` → Adds padding

---

### Featured Images

Some images use:

```html
col-span-2 row-span-2
```

This makes them:

* Span 2 columns
* Span 2 rows
* Appear larger than other images

---

### Image Styling

```html
class="aspect-square py-2"
```

* `aspect-square` → Maintains 1:1 ratio
* `py-2` → Adds vertical padding

---

## 🎯 How to Run

1. Copy the HTML code into an `index.html` file.
2. Open the file in your browser.
3. No installation required (Tailwind is loaded via CDN).

---

## 💡 Possible Improvements

* Make layout fully responsive (`md:grid-cols-4`, `sm:grid-cols-2`)
* Add hover effects (`hover:scale-105 transition`)
* Center the container (`mx-auto`)
* Fix background class typo (`bg-bu-900` → `bg-blue-900`)
* Style the tagline text properly using `col-span-4 text-center`

---

## ✨ Example Enhancement

```html
<i class="col-span-4 text-center text-2xl font-semibold text-black">
  With Nike, every step finds its destiny.
</i>
