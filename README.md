# 📸 SnapMark – Screenshot Editor & Annotation Tool

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Pure Vanilla JS](https://img.shields.io/badge/Vanilla-HTML5%20%2F%20JS-yellow.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Privacy First](https://img.shields.io/badge/Privacy-100%25%20Client--Side-brightgreen.svg)](#-privacy--security)
[![Zero Dependencies](https://img.shields.io/badge/Dependencies-Zero-success.svg)](#-zero-dependencies)
![Views](https://api.visitorbadge.io/api/visitors?path=mianlabib%2Fsnapmark&label=REPO%20VIEWS&countColor=%234f46e5)

> **SnapMark** is a fast, lightweight, and privacy-first in-browser screenshot editor and annotation tool. Annotate images, blur sensitive credentials, draw arrows, add numbered steps, and export crisp PNGs in seconds—with zero installation and zero cloud uploads.

---

## ✨ Features

- 🔒 **100% Client-Side Privacy:** Your images never leave your browser. No server uploads, no analytics, no external tracking.
- 📋 **Seamless Clipboard Workflow:** Press `Ctrl + V` (`⌘ + V`) anywhere to paste an image instantly, or drag & drop files.
- 🎨 **Rich Annotation Toolkit:**
  - **Rectangle & Circle:** Highlight important UI elements or areas.
  - **Arrow & Line:** Guide viewers directly to key points.
  - **Freehand Pen & Highlighter:** Sketch freely or mark text with semi-transparent highlights.
  - **Text Tool:** Add crisp headings and explanatory labels.
  - **Numbered Step Badges:** Add sequence markers (`1`, `2`, `3`...) automatically with auto-contrasting numbers for guides and bug reports.
  - **Pixelate / Blur Tool:** Obscure sensitive information (passwords, tokens, emails, API keys) quickly.
  - **Crop Tool:** Trim the canvas to the exact region you need.
- ⚡ **Instant Copy & Download:**
  - Copy directly back to clipboard with `Ctrl + C` (`⌘ + C`) to paste straight into Slack, Teams, Discord, Jira, or GitHub.
  - Export lossless PNG files with `Ctrl + S` (`⌘ + S`).
- 🌓 **Dark & Light Mode:** Seamlessly toggles themes with auto OS-preference detection and `localStorage` persistence.
- 🔍 **Zoom & Fit Canvas:** Smooth mouse-wheel zooming, fit-to-screen, and click-to-reset 100% scale.
- ↩️ **Full History Stack:** Comprehensive multi-level Undo (`Ctrl + Z`) and Redo (`Ctrl + Y`).

---

## ⌨️ Keyboard Shortcuts Cheat Sheet

| Action | Shortcut (Windows / Linux) | Shortcut (macOS) |
| :--- | :--- | :--- |
| **Paste Image** | `Ctrl + V` | `⌘ + V` |
| **Copy Result** | `Ctrl + C` | `⌘ + C` |
| **Download PNG** | `Ctrl + S` | `⌘ + S` |
| **Undo** | `Ctrl + Z` | `⌘ + Z` |
| **Redo** | `Ctrl + Y` or `Ctrl + Shift + Z` | `⌘ + Y` or `⌘ + Shift + Z` |
| **Duplicate Object** | `Ctrl + D` | `⌘ + D` |
| **Delete Selection** | `Delete` / `Backspace` | `Delete` / `Backspace` |
| **Nudge Selection** | `Arrow Keys` (Shift for 10px) | `Arrow Keys` (Shift for 10px) |
| **Confirm Crop** | `Enter` | `Return` |
| **Cancel Crop / Deselect** | `Escape` | `Escape` |

### Tool Shortcuts

| Key | Tool | Key | Tool |
| :---: | :--- | :---: | :--- |
| `V` | **Select / Move** | `H` | **Highlight** |
| `S` / `R` | **Square / Rectangle** | `T` | **Text** |
| `O` | **Circle / Ellipse** | `N` | **Step Number Badge** |
| `A` | **Arrow** | `B` | **Blur / Pixelate** |
| `L` | **Line** | `C` | **Crop** |
| `P` | **Freehand Pen** | | |

---

## 🛡️ Privacy & Security

Most online image editors upload your screenshots to remote cloud servers to process them. SnapMark is built with privacy as the core priority:

- All rendering and manipulations are performed directly inside the browser using the HTML5 Canvas API.
- Works 100% offline without an active internet connection.
- Ideal for handling sensitive internal dashboards, credentials, personal data, and confidential tickets.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE) — free for personal and commercial use.

