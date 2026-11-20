<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:1d4ed8&height=180&section=header&text=color-vision-preview&fontSize=42&fontColor=ffffff&animation=fadeIn" alt="Color Vision Preview banner" width="100%"/>

<a href="https://github.com/CyberLoop-dev/color-vision-preview">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1100&color=22d3ee&center=true&vCenter=true&width=700&lines=Color+Vision+Preview;Small+tools.+Clear+feedback.+Local+first." alt="Typing title"/>
</a>

<p><strong>Simulate common color-vision deficiencies on local images and color swatches in a private browser workspace.</strong></p>

[![License](https://img.shields.io/github/license/CyberLoop-dev/color-vision-preview)](LICENSE)
[![Language](https://img.shields.io/github/languages/top/CyberLoop-dev/color-vision-preview)](https://github.com/CyberLoop-dev/color-vision-preview)
[![Stars](https://img.shields.io/github/stars/CyberLoop-dev/color-vision-preview?style=flat)](https://github.com/CyberLoop-dev/color-vision-preview/stargazers)
[![Last commit](https://img.shields.io/github/last-commit/CyberLoop-dev/color-vision-preview)](https://github.com/CyberLoop-dev/color-vision-preview/commits/main)

<img src="assets/overview.svg" alt="Color Vision Preview project illustration" width="100%"/>

</div>

## ✨ Overview

Simulate common color-vision deficiencies on local images and color swatches in a private browser workspace. **Color Vision Preview** is a small, focused Node.js + browser JavaScript project designed to be easy to inspect, run, and extend. It works locally and keeps the workflow straightforward.

## 🚀 Features

- ✨ 🖼️ Load an image directly into the browser canvas.
- ✨ 🎛️ Preview protanopia, deuteranopia, tritanopia, grayscale, and normal modes.
- ✨ 🎨 Compare a built-in color palette under the selected simulation.
- ✨ 📥 Export the transformed canvas as PNG; no upload endpoint exists.

## 🖥️ Demo

Run `npm start`, open `http://127.0.0.1:4173`, choose an image, and switch simulation modes. The sample palette updates with the image.

## ⚡ Quick Start

```bash
npm start
```

See the command-specific notes below if the project needs an input file or a browser tab.

## 🧰 Tech Stack

- **Primary language:** Node.js + browser JavaScript
- **Runtime:** Free, locally installed tooling
- **Dependencies:** Minimal; see the manifest in this repository

## 📁 Folder Structure

```text
color-vision-preview/
├── assets/
│   └── overview.svg
├── README.md
├── LICENSE
└── source files and project manifest
```

## 🗺️ Roadmap

- [ ] Add user-defined palette swatches.
- [ ] Add side-by-side original and simulated views.
- [ ] Add keyboard-accessible preset controls.

## 🤝 Contributing

Issues and pull requests are welcome. Keep changes focused, document behavior, and add tests for new parsing or transformation rules.

## 📄 License

Released under the [MIT License](LICENSE).

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1d4ed8,100:0f172a&height=110&section=footer" alt="Animated wave footer" width="100%"/>
</div>
