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
    Akıcı ve odaklanmış bir okuma deneyimi sunan minimalist web novel reader.
  </p>

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Lucide Icons](https://img.shields.io/badge/Lucide-FF69B4?style=for-the-badge&logo=lucide&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)

  <p>
    <a href="#features">Özellikler</a> •
    <a href="#technologies">Teknolojiler</a> •
    <a href="#installation">Kurulum</a> •
    <a href="#configuration">Konfigürasyon</a> •
    <a href="#license">Lisans</a> •
    <a href="#gallery">Galeri</a>
  </p>

  <br />
  <br />
</div>

## 📷 Demo Linki

- [https://xkintaro.github.io/text-reader/](https://xkintaro.github.io/text-reader/)

## 📋 Hakkında

**Text Reader**, odaklanma odaklı bir okuma deneyimi için tasarlanmış premium, minimalist bir web novel reader arayüzüdür. Yumuşak geçişler, klavye kısayolları ve kalıcı okuma ilerlemesi sunan şık ve modern bir UI sağlar.

## ✨ Özellikler <a id="features"></a>

- **Premium Estetik:** Glassmorphism efektleri ve altın sarısı vurgularla donatılmış, dark-themed (karanlık tema) arayüz.
- **Kesintisiz Navigasyon:** Bölümler arasında geçiş yapmak için kullanımı kolay yönlendirme butonları.
- **Bölüm Kütüphanesi:** Hızlı bölüm seçimi ve doğrudan geçiş yapmak için modal tabanlı bir kütüphane.
- **Kalıcı Okuma:** LocalStorage kullanarak en son okuduğunuz bölümü otomatik olarak hatırlar.
- **Klavye Kısayolları:**
  - `ArrowLeft` / `ArrowRight`: Bölümler arasında geçiş yapın.
  - `M`: Kütüphaneyi/menüyü açın.
  - `ESC`: Kütüphaneyi/menüyü kapatın.
- **Hızlı Performans:** Son yüklenen bölümler için in-memory caching (bellek içi önbelleğe alma).
- **Responsive Tasarım:** Hem mobil cihazlar hem de büyük ekranlar için optimize edilmiştir.
- **Deep Linking:** Okuma ilerlemesini URL hash'i ile senkronize eder (örn. `index.html#42`).

## 🛠️ Teknolojiler <a id="technologies"></a>

- **HTML5**: Uygulamanın temel iskeletini ve sayfa yapısını oluşturmak için kullanıldı.
- **JavaScript**: Bölüm geçişleri, klavye kısayolları, LocalStorage yönetimi ve dinamik veri yükleme işlemlerini sağlar.
- **Tailwind CSS**: Modern, minimalist ve responsive arayüz tasarımını hızlıca stilize etmek için tercih edildi.
- **Lucide Icons**: Arayüzde kullanılan modern, temiz ve şık vektörel ikon setini sağlar.

## 🚀 Kurulum <a id="installation"></a>

### Gereksinimler

Tailwind CLI çalıştırmak ve projeyi yerel olarak sunmak için sisteminizde [Node.js](https://nodejs.org/) kurulu olması gerekir.

### Kurulum

Projeyi yerel makinenizde çalıştırmak için aşağıdaki adımları izleyin:

1. **Repository'yi Klonlayın:**

   ```bash
   git clone https://github.com/xkintaro/text-reader.git
   cd text-reader
   ```

2. **Bağımlılıkları Yükleyin:**

   ```bash
   npm install
   ```

3. **Geliştirici Sunucusunu Başlatın:**

   ```bash
   npm start
   ```

   Tarayıcınızda `http://localhost:5173` adresine giderek projeyi görüntüleyebilirsiniz.

## ⚙️ Konfigürasyon <a id="configuration"></a>

Text Reader son derece esnektir. Varsayılan olarak dosyaları belirli bir formatta beklese de, `script.js` dosyasındaki `CONFIG` objesi aracılığıyla davranışını kolayca özelleştirebilirsiniz.

### Varsayılan Beklentiler

Okuyucu, varsayılan olarak `chapters/` dizinini tarayarak `chapter-1.txt`, `chapter-2.txt` gibi adlandırılmış dosyaları arar.

### Okuyucuyu Özelleştirme

`script.js` dosyasını açın ve dosyanın en üstündeki `CONFIG` sabitini değiştirin:

```javascript
const CONFIG = {
  chapterPrefix: "chapter-",     // Dosyalarınızın ön eki (prefix)
  chapterExtension: ".txt",      // Dosya uzantısı (extension)
  basePath: "./chapters/",       // Bölümlerin saklandığı klasör yolu (basePath)
  totalChapters: 2235,           // Toplam bölüm sayısı
  storageKey: "lastChapter",     // İlerleme için LocalStorage anahtarı (key)
};
```

<img src="md/20260414142727595.jpg" width="100%" />

## 📄 Lisans <a id="license"></a>

Bu proje MIT Lisansı altında lisanslanmıştır. Detaylar için [LICENSE](LICENSE) dosyasını inceleyebilirsiniz.

## 🖼️ Galeri <a id="gallery"></a>

<img src="md/20260414142727652.jpg" width="%100" />

#

<img src="md/20260414142727721.jpg" width="auto" />

#

<p align="center">
  <sub>❤️ Developed by "Mustafa TAŞAL" (kintaro)</sub>
</p>