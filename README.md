<a href="README.md">
 <img src="https://img.shields.io/badge/Language-English-blue?style=flat-square&logo=google-translate&logoColor=white" alt="English">
</a>
<a href="README-TR.md">
 <img src="https://img.shields.io/badge/Dil-Türkçe-red?style=flat-square&logo=google-translate&logoColor=white" alt="Türkçe">
</a>

  <br />
  <br />

<div align="center">
  <img src="kintaro.png" width="120" height="120" />
  <br />
  <br />

  <p>
    Minimalist web novel reader with smooth and focused reading experience.
  </p>

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Lucide Icons](https://img.shields.io/badge/Lucide-FF69B4?style=for-the-badge&logo=lucide&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)

  <p>
    <a href="#features">Features</a> •
    <a href="#technologies">Technologies</a> •
    <a href="#installation">Installation</a> •
    <a href="#configuration">Configuration</a> •
    <a href="#license">License</a> •
    <a href="#gallery">Gallery</a>
  </p>

  <br />
  <br />
</div>

## 📷 Demo Link

- [https://xkintaro.github.io/text-reader/](https://xkintaro.github.io/text-reader/)

## 📋 About

**Text Reader** is a premium, minimalist web novel reader interface designed for a focus-oriented reading experience. It provides a sleek, modern UI with smooth transitions, keyboard shortcuts, and persistent reading progress.

## ✨ Features <a id="features"></a>

- **Premium Aesthetics:** Dark-themed interface with glassmorphism effects and gold accents.
- **Seamless Navigation:** Easy-to-use navigation buttons for moving between chapters.
- **Chapter Library:** A modal-based library for quick chapter selection and direct jumping.
- **Persistent Reading:** Automatically remembers your last read chapter using LocalStorage.
- **Keyboard Shortcuts:**
  - `ArrowLeft` / `ArrowRight`: Navigate between chapters.
  - `M`: Open library/menu.
  - `ESC`: Close library/menu.
- **Fast Performance:** In-memory caching for recently loaded chapters.
- **Responsive Design:** Optimized for both mobile devices and large screens.
- **Deep Linking:** Syncs reading progress with the URL hash (e.g., `index.html#42`).

## 🛠️ Technologies <a id="technologies"></a>

- **HTML5**: Used to build the core structure and layout of the application.
- **JavaScript**: Powers all interactive functionality, including chapter navigation, keyboard shortcuts, LocalStorage management, and dynamic content rendering.
- **Tailwind CSS**: Utilized for rapid styling to create a premium, minimalist, and responsive user interface.
- **Lucide Icons**: Provides the modern, clean vector icons used throughout the user interface.

## 🚀 Installation <a id="installation"></a>

### Prerequisites

You need [Node.js](https://nodejs.org/) installed on your system to run the Tailwind CLI and serve the project locally.

### Installation

Follow these steps to run the project on your local machine:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/xkintaro/text-reader.git
   cd text-reader
   ```

2. **Install Dependencies:**

   ```bash
   npm install
   ```

3. **Start the Development Server:**

   ```bash
   npm start
   ```

You can view the project by going to `http://localhost:5173` in your browser.

## ⚙️ Configuration <a id="configuration"></a>

Text Reader is highly flexible. While it expects files in a specific format by default, you can easily customize the behavior via the `CONFIG` object in `script.js`.

### Default Expectations

By default, the reader scans the `chapters/` directory for files named `chapter-1.txt`, `chapter-2.txt`, etc.

### Customizing the Reader

Open `script.js` and modify the `CONFIG` constant at the top of the file:

```javascript
const CONFIG = {
  chapterPrefix: "chapter-",     // Prefix of your files
  chapterExtension: ".txt",      // File extension
  basePath: "./chapters/",       // Folder where chapters are stored
  totalChapters: 2235,           // Total number of chapters
  storageKey: "lastChapter",     // LocalStorage key for progress
};
```

<img src="md/20260414142727595.jpg" width="100%" />

## 📄 License <a id="license"></a>

This project is licensed under the MIT License. You can check the [LICENSE](LICENSE) file for details.

## 🖼️ Gallery <a id="gallery"></a>

<img src="md/20260414142727652.jpg" width="%100" />

#

<img src="md/20260414142727721.jpg" width="auto" />

#

<p align="center">
  <sub>❤️ Developed by "Mustafa TAŞAL" (kintaro)</sub>
</p>