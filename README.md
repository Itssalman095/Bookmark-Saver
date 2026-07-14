# 🔖 Bookmark Saver

A simple, lightweight bookmark manager built with vanilla **HTML**, **CSS**, and **JavaScript**. Save and organize your favorite links right in the browser — no backend, no build step, no dependencies.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

---

## ✨ Features

- ➕ **Add bookmarks** with a name and URL
- ✅ **URL validation** — must start with `http://` or `https://`
- 🗑️ **Remove bookmarks** with one click
- 💾 **Persistent storage** — bookmarks are saved to `localStorage`, so they're still there when you reload
- 🎨 **Clean, minimal UI** with a green accent theme

---

## 🚀 Demo

[Live Demo](https://itssalman095.github.io/Bookmark-Saver/)

---

## 📦 Getting Started

No installation, no build tools, no dependencies.

### Clone the repo

```bash
git clone https://github.com/Itssalman095/bookmark-saver.git
cd bookmark-saver
```

Then just open `index.html` in your browser.

### Or download directly

1. Click the green **Code** button on GitHub
2. Select **Download ZIP**
3. Extract it and open `index.html`

---

## 🛠️ Usage

1. Type a **name** for your bookmark
2. Type the **URL** (must start with `http://` or `https://`)
3. Click **Add Bookmark**
4. Click **Remove** on any bookmark to delete it

Your bookmarks persist automatically — no save button needed.

---

## 📁 Project Structure

```
bookmark-saver/
├── index.html      # Markup
├── style.css       # Styling
└── index.js        # App logic (add, remove, persist to localStorage)
```

---

## ⚙️ How It Works

- Bookmarks are stored as an array of `{ name, url }` objects under the `bookmarks` key in `localStorage`.
- On page load, `loadBookmarks()` reads from storage and renders each saved bookmark.
- Adding a bookmark validates both fields, appends it to the DOM, and saves it to storage.
- Removing a bookmark deletes it from the DOM and filters it out of storage.

---

## 🌐 Browser Compatibility

Works in any modern browser that supports `localStorage` (Chrome, Firefox, Safari, Edge). Private/Incognito windows may clear storage on close.

---

## 🗺️ Roadmap

Ideas for future versions:

- [ ] Edit existing bookmarks
- [ ] Tags/categories and filtering
- [ ] Search bookmarks
- [ ] Import/export as JSON
- [ ] Dark mode
- [ ] Auto-fetch favicon for each link

---

## 📝 License

MIT — free to use, modify, and distribute.

---

<p align="center">
  Made with HTML, CSS & JavaScript
</p>
