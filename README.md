# Assignment-newspaper

# 📰 Newspaper Website Layout

A simple **newspaper-style webpage** created using **HTML5 and CSS3**. This project demonstrates how CSS columns can be used to arrange text into a newspaper-like layout.

## 📌 Project Overview

The webpage is designed to look like a basic digital newspaper called **"Times Of India"**. It includes a newspaper heading, a scrolling latest-news banner, and multiple columns containing article-style content.

## 🛠️ Technologies Used

* **HTML5**
* **CSS3**
* CSS Multi-Column Layout
* HTML `<marquee>` element

## ✨ Features

* 📰 Newspaper-style design
* 📑 Three-column text layout
* ➖ Column separators
* 📏 Custom column spacing
* 📢 Scrolling latest-news banner
* 🎨 Wheat-colored page background
* 📝 Multiple article sections
* 📱 Viewport configuration for responsive display

The project uses `column-count: 3` and a `column-rule` to create the newspaper columns.

## 📂 Project Structure

```text
📦 Newspaper-Layout
 ├── 📄 newspaper.html
 └── 📄 README.md
```

## 🧩 Main Layout

```text
┌─────────────────────────────────────────────┐
│              TIMES OF INDIA                 │
├─────────────────────────────────────────────┤
│       Latest Updated News Date              │
├──────────────┬──────────────┬───────────────┤
│   ARTICLE    │   ARTICLE    │    ARTICLE    │
│              │              │               │
│   Content    │   Content    │    Content    │
│              │              │               │
├──────────────┴──────────────┴───────────────┤
│              MORE ARTICLES                  │
├──────────────┬──────────────┬───────────────┤
│   ARTICLE    │   ARTICLE    │    ARTICLE    │
└──────────────┴──────────────┴───────────────┘
```

## 📚 CSS Concepts Demonstrated

### 1. CSS Columns

The project uses:

```css
column-count: 3;
column-rule: 3px solid black;
```

This divides content into three columns with vertical separators.

### 2. Column Gap

A `30px` gap is used between columns in one of the sections:

```css
column-gap: 30px;
```

### 3. Scrolling News

A `<marquee>` is used to display a scrolling news update at the top of the page.

## 🚀 How to Run

1. Clone this repository:

```bash
git clone https://github.com/your-username/your-repository.git
```

2. Open the project folder.
3. Open **`newspaper.html`** in a web browser.
4. The newspaper layout will be displayed.

## 🎓 Learning Objectives

This project helps demonstrate:

* HTML page structure
* CSS styling
* CSS multi-column layouts
* `column-count`
* `column-rule`
* `column-gap`
* Basic typography
* Creating newspaper-style designs

## 👨‍💻 Author

**Anshuman Singh**

## ⭐ Project

**Project Type:** HTML & CSS Practice Project
**Topic:** Newspaper Layout
**File:** `newspaper.html`

---

⭐ **If you like this project, consider giving the repository a star!**
