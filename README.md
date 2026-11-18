<a href="README.md">
  <img src="https://img.shields.io/badge/Language-English-blue?style=flat-square&logo=google-translate&logoColor=white" alt="English">
</a>
<a href="README-TR.md">
  <img src="https://img.shields.io/badge/Language-Türkçe-red?style=flat-square&logo=google-translate&logoColor=white" alt="Türkçe">
</a>

  <br />
  <br />

<div align="center">
  <img src="mascot.png" width="120" height="120" />
  <br />
  <br />

  <p>
     A minimalist web reader for reading novels chapter by chapter.
  </p>

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Lucide Icons](https://img.shields.io/badge/Lucide-FF69B4?style=for-the-badge&logo=lucide&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)

  <p>
    <a href="#warning">Warning</a> •
    <a href="#demo">Demo</a> •
    <a href="#about">About</a> •
    <a href="#features">Features</a> •
    <a href="#tech">Tech</a> •
    <a href="#setup">Setup</a> •
    <a href="#license">License</a>
  </p>

  <br />
  <br />
</div>

## <a id="warning"></a> ⚠️ Warning

This project was first published as **Aether Reader** and later renamed to **Text Reader**. It has now been renamed to **Novel Reader** to better describe what it does. As part of this change, the old logo was replaced with a new logo that is also used as the favicon.

## <a id="demo"></a> 📷 Demo

- [https://xkintaro.github.io/novel-reader/](https://xkintaro.github.io/novel-reader/)

## <a id="about"></a> 📋 About

**Novel Reader** is a minimalist web reader built for long reading sessions. Chapters are plain text files in the `chapters/` folder, and the reader loads them one by one on a dark page with gold accents.

Move between chapters with the buttons or the arrow keys, or open the library to jump straight to any chapter. The reader remembers the last chapter you read and keeps the chapter number in the address bar, so you can pick up where you left off or share a link to a specific chapter.

## <a id="features"></a> ✨ Features

- **Chapter navigation**: Move to the previous or next chapter with the buttons at the bottom of the page.
- **Library**: Pick a chapter from the list or type a chapter number to jump straight to it.
- **Keyboard shortcuts**: Use the left and right arrow keys to change chapters, `M` to open the library and `Esc` to close it.
- **Reading progress**: The reader remembers your last chapter and opens it the next time you visit.
- **Chapter links**: The chapter number is kept in the address, such as `index.html#3`, so you can open a chapter directly.
- **Fast loading**: Chapters you have already opened are kept in memory and load instantly.

## <a id="tech"></a> 🛠️ Tech

`HTML` · `JavaScript` · `Tailwind CSS` · `Lucide`

## <a id="setup"></a> 🚀 Setup

### Requirements

- **Node.js**

### Step-by-Step Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/xkintaro/novel-reader.git
   cd novel-reader
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Start the server**

   ```bash
   npm start
   ```

Open the app at [http://localhost:3000](http://localhost:3000).

If you change the styles, run `npm run dev` in a separate terminal to rebuild `output.css` with Tailwind CSS.

### Configuration

The reader looks for files named `chapter-1.txt`, `chapter-2.txt` and so on in the `chapters/` folder. You can change this in the `CONFIG` object at the top of `script.js`:

```javascript
const CONFIG = {
    chapterPrefix: 'chapter-',     // Prefix of your files
    chapterExtension: '.txt',      // File extension
    basePath: './chapters/',       // Folder where chapters are stored
    totalChapters: 6,              // Total number of chapters
    storageKey: 'lastChapter'      // LocalStorage key for progress
};
```

## <a id="license"></a> 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

#

<p align="center">
  <sub>❤️ Developed by "Mustafa TAŞAL" (kintaro)</sub>
</p>
