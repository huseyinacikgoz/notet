# NotEt

<div align="center">
  <img src="favicon/apple-touch-icon.png" width="128" height="128" alt="NotEt Logo">
</div>

<div align="center">

**🌐 Dil Seçimi | Language Selection**

[🇹🇷 Türkçe](#türkçe) | [🇬🇧 English](#english)

</div>

---

<a id="türkçe"></a>

<div align="center">

**Tarayıcı Tabanlı, Minimalist ve %100 Yerel Not Alma Uygulaması**


[![Sürüm](https://img.shields.io/badge/sürüm-v0.0.3-black?style=flat-square)](https://huseyinacikgoz.com.tr/notet/)
[![Lisans](https://img.shields.io/badge/lisans-MIT-blue?style=flat-square)](LICENSE)
[![Durum](https://img.shields.io/badge/durum-Yayında-green?style=flat-square)](https://huseyinacikgoz.com.tr/notet/)

</div>

## 📖 Hakkında

**NotEt**, verilerinizi asla bir sunucuya göndermeden, tamamen tarayıcınızın yerel hafızasında (LocalStorage) saklayan, açık kaynaklı ve modern bir not defteridir.

Ekstra hiçbir kurulum gerektirmeden, sadece tarayıcınızı kullanarak notlarınızı alabilir, şifreleyerek yedekleyebilir ve güvenle saklayabilirsiniz. Minimalist tasarımı sayesinde odağınız sadece notlarınızda olur.

## ✨ Özellikler

### 🔒 Mahremiyet ve Güvenlik
- **Yerel Depolama**: Tüm verileriniz cihazınızda, tarayıcınızın güvenli hafızasında (LocalStorage) tutulur.
- **Sunucusuz**: Hiçbir veriniz dışarıdaki bir sunucuya gönderilmez.
- **İzleyicisiz**: Rahatsız edici takip kodları veya analitik araçları (tracker) içermez.

### ⚡ Performans
- **Anında Erişim**: Bekleme veya yükleme süresi yoktur, saniyeler içinde not almaya başlayın.
- **Çevrimdışı Mod**: İnternet bağlantınız olmasa bile tam fonksiyonel çalışır.
- **Hafif**: Modern web teknolojileri ile geliştirilmiş, kaynak tüketmeyen yapı.

### 📂 Kullanım Kolaylığı
- **Bölünmüş Yapı**: Kategori sistemi ile iş, okul veya kişisel notlarınızı ayırın.
- **Güvenli Yedekleme**: AES-GCM şifreleme algoritmasıyla notlarınızın yedeğini alın.
- **Responsive Tasarım**: Telefondan tablete, tüm cihazlarda kusursuz görünüm.

## 🚀 Kullanım

### Canlı Versiyon
Uygulamayı indirmeden kullanmak için: [huseyinacikgoz.com.tr/notet](https://huseyinacikgoz.com.tr/notet/)

### Yerel Kurulum

1. **Projeyi klonlayın:**
   ```bash
   git clone https://github.com/huseyinacikgoz/NotEt.git
   cd notet
   ```

2. **Yerel sunucu başlatın:**
   LocalStorage ve modül sisteminin düzgün çalışması için basit bir HTTP sunucusu önerilir.
   ```bash
   # Python ile
   python3 -m http.server

   # Veya Node.js ile (varsa)
   npx serve .
   ```

3. **Tarayıcıda açın:**
   ```
   http://localhost:8000
   ```

## 🛠️ Teknolojiler

- **HTML5** & **CSS3** (Semantik yapı ve modern stil)
- **Vanilla JavaScript** (ES6+ Modülleri)
- **TailwindCSS** (Hızlı UI geliştirme)
- **LocalStorage API** (Persistent veri depolama)
- **Web Crypto API** (Güvenlik)

## 📁 Proje Yapısı

```
notet/
├── css/
│   └── styles.css         # Ana stil dosyası
├── js/
│   ├── app.js             # Uygulama giriş noktası
│   ├── store.js           # Veri ve durum yönetimi
│   ├── crypto-utils.js    # Şifreleme fonksiyonları
│   └── utils.js           # Yardımcı araçlar
├── components/            # UI bileşenleri
├── index.html             # Landing page & SPA Uygulaması
├── privacy.html           # Gizlilik politikası
└── README.md              # Proje dokümantasyonu
```

## 🎯 Nasıl Kullanılır?

1. **Başlangıç**: Ana sayfadaki "Hemen Başla" butonuna tıklayarak not alma arayüzüne geçin.
2. **Not Ekleme**: Sağ alttaki veya menüdeki "+" butonunu kullanarak yeni not oluşturun.
3. **Kategoriler**: Notlarınızı renklere ve kategorilere göre ayırarak düzeni sağlayın.
4. **Yedekleme**: Ayarlar menüsünden "Yedeği İndir" diyerek verilerinizi şifreli bir dosya (.json) olarak bilgisayarınıza kaydedin.
5. **Geri Yükleme**: İndirdiğiniz yedek dosyasını "Yedeği Yükle" seçeneği ile geri yükleyerek notlarınıza tekrar erişin.

## 📄 Lisans

Bu proje [MIT Lisansı](LICENSE) altında lisanslanmıştır. Özgürce kullanabilir, değiştirebilir ve dağıtabilirsiniz.

## 👨‍💻 Geliştirici

**Hüseyin Açıkgöz**

- 🌐 Website: [huseyinacikgoz.com.tr](https://huseyinacikgoz.com.tr)
- 📧 Email: [mail@huseyinacikgoz.com.tr](mailto:mail@huseyinacikgoz.com.tr)
- 🐦 Twitter/X: [@huseyinacikgoz_](https://x.com/huseyinacikgoz_)
- 💻 GitHub: [@huseyinacikgoz](https://github.com/huseyinacikgoz)

## 🤝 Katkıda Bulunma

Katkılarınızı bekliyoruz! Lütfen:

1. Fork edin
2. Feature branch oluşturun (`git checkout -b feature/harika-ozellik`)
3. Değişikliklerinizi commit edin (`git commit -m 'Yeni özellik eklendi'`)
4. Branch'inizi push edin (`git push origin feature/harika-ozellik`)
5. Pull Request açın

## 🔗 Bağlantılar

- [🌐 Canlı Demo](https://huseyinacikgoz.com.tr/notet/)
- [🐞 Hata Bildir](https://github.com/huseyinacikgoz/NotEt/issues)

---

<div align="center">

**⭐ Beğendiyseniz yıldız vermeyi unutmayın! ⭐**

Made with ❤️ by [Hüseyin Açıkgöz](https://huseyinacikgoz.com.tr)

</div>

---

<div align="center">

<a id="english"></a>

# 🇬🇧 English Version

</div>

---

# NotEt

<div align="center">
  <img src="favicon/apple-touch-icon.png" width="128" height="128" alt="NotEt Logo">
</div>

<div align="center">

**Browser-Based, Minimalist and 100% Local Note-Taking Application**

[![Version](https://img.shields.io/badge/version-v0.0.3-black?style=flat-square)](https://huseyinacikgoz.com.tr/notet/)
[![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)](LICENSE)
[![Status](https://img.shields.io/badge/status-Live-green?style=flat-square)](https://huseyinacikgoz.com.tr/notet/)

</div>

## 📖 About

**NotEt** is an open-source, modern notebook that stores your data entirely in your browser's local storage (LocalStorage), never sending it to any server.

Without any extra installation, you can take notes using just your browser, backup them with encryption, and store them safely. Thanks to its minimalist design, your focus stays only on your notes.

## ✨ Features

### 🔒 Privacy & Security
- **Local Storage**: All your data is kept in your device's secure browser memory (LocalStorage).
- **Serverless**: None of your data is sent to an external server.
- **Tracker-free**: Contains no intrusive tracking codes or analytics tools.

### ⚡ Performance
- **Instant Access**: No waiting or loading time, start taking notes in seconds.
- **Offline Mode**: Fully functional even without an internet connection.
- **Lightweight**: Developed with modern web technologies, resource-efficient structure.

### 📂 Ease of Use
- **Organized Structure**: Separate your work, school, or personal notes with the category system.
- **Secure Backup**: Backup your notes with AES-GCM encryption algorithm.
- **Responsive Design**: Perfect appearance on all devices from phone to tablet.

## 🚀 Usage

### Live Version
To use the app without downloading: [huseyinacikgoz.com.tr/notet](https://huseyinacikgoz.com.tr/notet/)

### Local Installation

1. **Clone the project:**
   ```bash
   git clone https://github.com/huseyinacikgoz/NotEt.git
   cd notet
   ```

2. **Start a local server:**
   A simple HTTP server is recommended for LocalStorage and module system to work properly.
   ```bash
   # With Python
   python3 -m http.server

   # Or with Node.js (if available)
   npx serve .
   ```

3. **Open in browser:**
   ```
   http://localhost:8000
   ```

## 🛠️ Technologies

- **HTML5** & **CSS3** (Semantic structure and modern styling)
- **Vanilla JavaScript** (ES6+ Modules)
- **TailwindCSS** (Rapid UI development)
- **LocalStorage API** (Persistent data storage)
- **Web Crypto API** (Security)

## 📁 Project Structure

```
notet/
├── css/
│   └── styles.css         # Main style file
├── js/
│   ├── app.js             # Application entry point
│   ├── store.js           # Data and state management
│   ├── crypto-utils.js    # Encryption functions
│   └── utils.js           # Helper utilities
├── components/            # UI components
├── index.html             # Landing page & SPA App
├── privacy.html           # Privacy policy
└── README.md              # Project documentation
```

## 🎯 How to Use?

1. **Getting Started**: Click the "Start Now" button on the main page to access the note-taking interface.
2. **Add Note**: Create a new note using the "+" button in the bottom right or in the menu.
3. **Categories**: Organize your notes by colors and categories.
4. **Backup**: Save your data as an encrypted file (.json) by clicking "Download Backup" from the settings menu.
5. **Restore**: Restore your notes by loading the downloaded backup file with the "Load Backup" option.

## 📄 License

This project is licensed under the [MIT License](LICENSE). You can freely use, modify, and distribute it.

## 👨‍💻 Developer

**Hüseyin Açıkgöz**

- 🌐 Website: [huseyinacikgoz.com.tr](https://huseyinacikgoz.com.tr)
- 📧 Email: [mail@huseyinacikgoz.com.tr](mailto:mail@huseyinacikgoz.com.tr)
- 🐦 Twitter/X: [@huseyinacikgoz_](https://x.com/huseyinacikgoz_)
- 💻 GitHub: [@huseyinacikgoz](https://github.com/huseyinacikgoz)

## 🤝 Contributing

We welcome your contributions! Please:

1. Fork it
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 🔗 Links

- [🌐 Live Demo](https://huseyinacikgoz.com.tr/notet/)
- [🐞 Report Bug](https://github.com/huseyinacikgoz/NotEt/issues)

---

<div align="center">

**⭐ If you like it, don't forget to give it a star! ⭐**

Made with ❤️ by [Hüseyin Açıkgöz](https://huseyinacikgoz.com.tr)

</div>
