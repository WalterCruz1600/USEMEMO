# UserSearch with React Hooks (useMemo)

A lightweight, dependency-free example of a user search component built with React Hooks, optimized with `useMemo` and featuring localStorage persistence. No build tools or npm packages are required—just open the HTML file in your browser.

## 📋 Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Built With](#built-with)

## 🚀 Features

- **Case-Insensitive Search**: Filter users by name or description without worrying about capitalization.
- **Performance Optimization**: Leverage `useMemo` to avoid expensive recalculations on every render.
- **LocalStorage Persistence**: New users are saved to `localStorage` so they persist across page reloads.
- **No Dependencies**: Uses standalone React and ReactDOM from CDN, plus Babel for JSX—no npm or bundler needed.

## 🎥 Demo

## 🛠️ Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/WalterCruz1600/user-search-react-hooks.git
   cd user-search-react-hooks
   ```
2. **Open the HTML file**
   - Simply open `index.html` (or `UserSearch.html`) in your favorite browser.

## 📖 Usage

1. **Search**: Type in the search box to filter the list of users by name or description.
2. **Add a New User**:
   - Enter a name and description in the fields below.
   - Click **Add**. The new user will appear in the list and be saved to localStorage.
3. **Refresh**: Reload the page—the added users will still be there.

## 🗂️ Folder Structure

```
user-search-react-hooks/
├── index.html          # Main HTML with React, Babel, and component code
├── README.md           # This file
```

## 🛠️ Built With

- **React** (via CDN) – UI library
- **Babel Standalone** – JSX transformation in the browser
- **localStorage** – Browser persistence API
- **useState, useEffect, useMemo** – React Hooks for state, side-effects, and memoization


