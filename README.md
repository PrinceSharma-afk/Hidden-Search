# Hidden Search

A simple web project that demonstrates a hidden search input which becomes visible when a button is clicked. This project is perfect for improving UI/UX interactions and learning basic DOM manipulation with JavaScript.

## Live Demo

Check out the live demo here: [Hidden Search](https://princesharma-afk.github.io/Hidden-Search/)

## Features

- Hidden search input that toggles visibility on button click
- Clean and minimal design
- Fully responsive and lightweight
- Easy to integrate into any project

## How It Works

The search input is initially hidden using CSS. When the user clicks the toggle button, JavaScript updates the `display` property of the search input to make it visible.

```javascript
const btn = document.getElementById("searchBtn");
const search = document.getElementById("searchInput");

btn.addEventListener("click", () => {
    search.style.display = "block";
});
