# SharkReader

<p align="center">
  <img src="./icon.png" alt="SharkReader logo" width="120" />
</p>

<p align="center">
  <strong>A modern desktop reader for EPUB and PDF books.</strong>
</p>

<p align="center">
  <a href="#features">Features</a> ·
  <a href="#screenshots">Screenshots</a> ·
  <a href="#installation">Installation</a> ·
  <a href="#development">Development</a> ·
  <a href="#build">Build</a> ·
  <a href="#license">License</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/platform-Windows-blue" alt="Platform" />
  <img src="https://img.shields.io/badge/Electron-41.x-47848f" alt="Electron" />
  <img src="https://img.shields.io/badge/React-19.x-61dafb" alt="React" />
  <img src="https://img.shields.io/badge/Vite-8.x-646cff" alt="Vite" />
  <img src="https://img.shields.io/badge/license-ISC-green" alt="License" />
</p>

---

## About

**SharkReader** is a desktop reading app for Windows designed to make digital reading more organized, comfortable, and interactive.

It supports **EPUB** and **PDF** books, includes a full local library system, reading progress tracking, bookmarks, highlights, vocabulary tools, reading analytics, achievements, and an optional AI assistant that can help summarize, explain, translate, or analyze the current book context.

The app is built with **Electron**, **React**, and **Vite**, with all user data stored locally through **IndexedDB** and **localStorage**.

---

## Features

### Library management

- Import EPUB and PDF books.
- Drag and drop files directly into the app.
- Import individual books or entire folders.
- Edit book metadata such as title, author, cover, description, publisher, tags, series, category, rating, and status.
- Filter books by favorites, reading, unread, completed, wishlist, or custom category.
- Sort by last read, recently added, name, progress, or rating.
- Multiple library views, including grid, list, and optional addon-based layouts.

### EPUB reader

- EPUB 2 and EPUB 3 support through `epub.js`.
- Paginated and continuous reading modes.
- Single-page and double-page layouts.
- Adjustable font size.
- System font and optional OpenDyslexic support.
- Warm reading mode.
- Brightness controls.
- Table of contents navigation.
- Keyboard navigation.
- Page transition effects: none, fade, slide, and flip.
- Auto-scroll mode with adjustable speed.

### PDF reader

- PDF rendering through `pdfjs-dist`.
- Page-by-page navigation.
- Zoom controls.
- Jump to page.
- Single-page and double-page modes.
- Independent light and dark PDF reading modes.

### Reading tools

- Bookmarks with optional notes.
- Text highlights with multiple colors.
- Export quotes as PNG images.
- Global vocabulary system.
- Reading journal with session history.
- Reading progress tracking.
- Daily streaks.
- Yearly reading goal.
- Reading analytics dashboard.

### AI assistant

SharkReader includes an optional AI panel that works with the current reading context.

Supported providers:

- Groq
- Google Gemini
- OpenRouter
- xAI / Grok

The assistant can help with:

- Chapter summaries.
- Term explanations.
- Character analysis.
- Fragment translation.
- Open questions about the current book.

API keys are configured by the user and stored locally.

### Gamification

- Achievement system.
- Reading streaks.
- Progress statistics.
- Reading goals.
- Toast notifications when achievements are unlocked.

### Addons Workshop

SharkReader includes an addon system that allows optional features to be enabled or disabled from the app.

Examples include:

- Alternative library layouts.
- Focus mode.
- Floating table of contents.
- Auto-bookmarking.
- X-Ray style book notes.

---

## Screenshots

```txt
<img width="1919" height="1027" alt="image" src="https://github.com/user-attachments/assets/e1615bb8-04c5-494c-b722-190325f1fd17" />
<img width="1919" height="1009" alt="image" src="https://github.com/user-attachments/assets/acb97f3a-2837-4080-91de-1a8ed20c36e6" />
<img width="540" height="909" alt="image" src="https://github.com/user-attachments/assets/59ea79c3-9192-41f4-bcdc-22e1da393d3b" />
<img width="842" height="960" alt="image" src="https://github.com/user-attachments/assets/97939277-eaa9-4c66-b852-bae1f5c5fe84" />
<img width="381" height="794" alt="image" src="https://github.com/user-attachments/assets/22c76e0d-3dcc-48a3-80ad-5a272d2673a9" />
<img width="288" height="612" alt="image" src="https://github.com/user-attachments/assets/6ccbbb0f-b3d2-42fd-a1d1-ab5216587063" />
<img width="665" height="642" alt="image" src="https://github.com/user-attachments/assets/3d478843-64fd-4345-aa26-0c577ada1ac6" />
<img width="1919" height="1018" alt="image" src="https://github.com/user-attachments/assets/fb0b9a07-8dd6-4477-9fe2-1e1c205c169e" />
<img width="1885" height="443" alt="image" src="https://github.com/user-attachments/assets/cfa5d78f-4693-46d0-819d-7ffa1c9443db" />


