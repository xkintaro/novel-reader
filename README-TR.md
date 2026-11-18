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
     Romanları bölüm bölüm okumak için tasarlanmış sade bir web okuyucusu.
  </p>

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Lucide Icons](https://img.shields.io/badge/Lucide-FF69B4?style=for-the-badge&logo=lucide&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)

  <p>
    <a href="#warning">Uyarı</a> •
    <a href="#demo">Demo</a> •
    <a href="#about">Hakkında</a> •
    <a href="#features">Özellikler</a> •
    <a href="#tech">Teknolojiler</a> •
    <a href="#setup">Kurulum</a> •
    <a href="#license">Lisans</a>
  </p>

  <br />
  <br />
</div>

## <a id="warning"></a> ⚠️ Uyarı

Bu proje ilk olarak **Aether Reader** adıyla yayınlandı, ardından adı **Text Reader** olarak değiştirildi. Ne işe yaradığını daha iyi anlatması için adı şimdi de **Novel Reader** oldu. Bu değişiklikle birlikte eski logo, favicon olarak da kullanılan yeni bir logoyla değiştirildi.

## <a id="demo"></a> 📷 Demo

- [https://xkintaro.github.io/novel-reader/](https://xkintaro.github.io/novel-reader/)

## <a id="about"></a> 📋 Hakkında

**Novel Reader**, uzun okuma seansları için tasarlanmış sade bir web okuyucusudur. Bölümler `chapters/` klasöründeki düz metin dosyalarıdır ve okuyucu bunları altın rengi vurgulara sahip koyu bir sayfada tek tek yükler.

Bölümler arasında butonlarla veya ok tuşlarıyla geçiş yapın ya da kütüphaneyi açarak istediğiniz bölüme doğrudan atlayın. Okuyucu en son okuduğunuz bölümü hatırlar ve bölüm numarasını adres çubuğunda tutar. Böylece kaldığınız yerden devam edebilir veya belirli bir bölümün bağlantısını paylaşabilirsiniz.

## <a id="features"></a> ✨ Özellikler

- **Bölüm geçişi**: Sayfanın altındaki butonlarla önceki veya sonraki bölüme geçin.
- **Kütüphane**: Listeden bir bölüm seçin veya bölüm numarasını yazarak doğrudan o bölüme atlayın.
- **Klavye kısayolları**: Bölüm değiştirmek için sol ve sağ ok tuşlarını, kütüphaneyi açmak için `M`, kapatmak için `Esc` tuşunu kullanın.
- **Okuma ilerlemesi**: Okuyucu son bölümünüzü hatırlar ve bir sonraki ziyaretinizde onu açar.
- **Bölüm bağlantıları**: Bölüm numarası `index.html#3` gibi adreste tutulur, böylece bir bölümü doğrudan açabilirsiniz.
- **Hızlı yükleme**: Daha önce açtığınız bölümler bellekte tutulur ve anında yüklenir.

## <a id="tech"></a> 🛠️ Teknolojiler

`HTML` · `JavaScript` · `Tailwind CSS` · `Lucide`

## <a id="setup"></a> 🚀 Kurulum

### Gereksinimler

- **Node.js**

### Adım Adım Kurulum

1. **Depoyu klonlayın**

   ```bash
   git clone https://github.com/xkintaro/novel-reader.git
   cd novel-reader
   ```

2. **Bağımlılıkları yükleyin**

   ```bash
   npm install
   ```

3. **Sunucuyu başlatın**

   ```bash
   npm start
   ```

Uygulamayı şu adreste açın: [http://localhost:3000](http://localhost:3000).

Stilleri değiştirirseniz `output.css` dosyasını Tailwind CSS ile yeniden oluşturmak için ayrı bir terminalde `npm run dev` komutunu çalıştırın.

### Yapılandırma

Okuyucu, `chapters/` klasöründe `chapter-1.txt`, `chapter-2.txt` gibi adlandırılmış dosyaları arar. Bunu `script.js` dosyasının başındaki `CONFIG` nesnesinden değiştirebilirsiniz:

```javascript
const CONFIG = {
    chapterPrefix: 'chapter-',     // Prefix of your files
    chapterExtension: '.txt',      // File extension
    basePath: './chapters/',       // Folder where chapters are stored
    totalChapters: 6,              // Total number of chapters
    storageKey: 'lastChapter'      // LocalStorage key for progress
};
```

## <a id="license"></a> 📄 Lisans

Bu proje MIT Lisansı altında lisanslanmıştır. Detaylar için [LICENSE](LICENSE) dosyasına bakabilirsiniz.

#

<p align="center">
  <sub>❤️ Developed by "Mustafa TAŞAL" (kintaro)</sub>
</p>
