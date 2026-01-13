<p align="center">
  <h1 align="center">EASY_EDITOR</h1>

  <p align="center">
    <a href="https://github.com/sadbath/EASY_EDITOR/commits/main">
      <img src="https://img.shields.io/github/last-commit/sadbath/EASY_EDITOR?style=for-the-badge" alt="Last Commit">
    </a>
    <a href="https://github.com/sadbath/EASY_EDITOR/blob/main/LICENSE">
      <img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" alt="License">
    </a>
    <a href="https://sadbath.github.io/EASY_EDITOR">
      <img src="https://img.shields.io/badge/Visit-Site-brightgreen?style=for-the-badge" alt="Site">
    </a>
  </p>
</p>

---

## Overview

**EASY_EDITOR** is a high-performance, browser-based code editor designed for developers and designers. It combines:

- **Neovim-inspired workflow**: keyboard-driven, Vim-style commands
- **Gruvbox color palette**: clean, retro terminal aesthetic
- **CodeMirror**: fast, syntax-aware editing for HTML, CSS, and JavaScript

It is fully static and client-side, enabling quick prototyping without any server or backend dependencies.

---

## Features

| Feature | Description |
|---------|-------------|
| **Editor** | CodeMirror-based with HTML, CSS, JS syntax highlighting and ghost text autocompletion. |
| **Live Preview** | Full-page live rendering; updates automatically as you type. |
| **File Management** | Create, upload, download, delete files with local storage persistence. |
| **Layouts** | Horizontal and vertical splits, focus mode, resizable panes. |
| **UI / UX** | Gruvbox-inspired terminal theme, status bar showing Vim mode and cursor position, fully responsive. |
| **Keyboard Shortcuts** | `Tab / Shift+Tab` indentation, `Ctrl+A` select all, `Ctrl-S` save, `Ctrl-Q` toggle file explorer, `Escape` to close modals or fullscreen preview. |
| **Ghost Engine** | Suggests HTML tags, CSS properties, and JS keywords in real time. |

---

## Demo

![EASY_EDITOR Preview](https://user-images.githubusercontent.com/sadbath/EASY_EDITOR/demo-screenshot.png)

The editor displays dual-pane **code + live preview**, fully responsive, with Vim-style navigation and Gruvbox theme.

---

## Quick Example

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Live Preview</title>
</head>
<body>
  <h1>Hello from EASY_EDITOR</h1>
  <p>Edit HTML, CSS, and JS with live feedback.</p>
</body>
</html>
