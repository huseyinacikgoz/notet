# Değişiklik Günlüğü

Tüm önemli değişiklikler bu dosyada belgelenecektir.

## [v0.0.3] - 2026-01-23

### 🚀 Yeni Özellikler
- **Client-Side Routing (SPA)**: Uygulama artık tek sayfa uygulaması olarak çalışıyor
  - URL her zaman temiz kalıyor (`/notet` - hash veya ek path yok)
  - Tarayıcı geri/ileri butonları düzgün çalışıyor
  - Sayfa yenilemesi olmadan hızlı geçişler

### 🎨 Tasarım İyileştirmeleri
- **Landing Page Optimizasyonu**: CTA butonları artık sayfa açıldığında hemen görünüyor
  - Hero section padding ve margin değerleri optimize edildi
  - Mobil cihazlarda daha iyi görünüm
- **Başlık Düzeltmesi**: "Güvenle Saklayın" kelimelerindeki boşluk sorunu giderildi

### 🐛 Hata Düzeltmeleri
- **Sidebar Navigasyonu**: Sol menüdeki linkler artık doğru çalışıyor (landing page'e geri dönmüyor)
- **Alt Sayfa Linkleri**: privacy.html, terms.html, contact.html'deki "Uygulamaya Git" butonları düzeltildi

### �️ Kaldırılan Dosyalar
- **notes.html**: Artık kullanılmıyor, tüm işlevsellik index.html'e taşındı (SPA mimarisi)

### �📄 Dokümantasyon
- README.md güncellendi (sürüm v0.0.3 olarak işaretlendi)
- CHANGELOG.md güncellendi

---

## [v0.0.2] - 2025-12-26

### 🎨 Tasarım İyileştirmeleri
- **Favicon Güncellemesi**: Favicon dosyaları yeniden düzenlendi ve `favicon/` klasörüne taşındı
  - Eski `favicon.svg` ve `logo.svg` dosyaları kaldırıldı
  - Yeni favicon yapısı ile tüm cihazlarda daha iyi görünüm sağlandı
  - `apple-touch-icon.png`, `favicon-16x16.png`, `favicon-32x32.png` eklendi
  - `site.webmanifest` ile PWA desteği iyileştirildi

### 🐛 Hata Düzeltmeleri
- **Notlar Sayfası**: Ana sayfa ikonu yerine not ikonu kullanılmaya başlandı
- **Mobil Görünüm**: Notlar sayfasında header elemanları üst tarafa hizalandı, not listesi için daha fazla dikey alan sağlandı
- **Sidebar İyileştirmeleri**: Mobil cihazlarda sidebar davranışı optimize edildi

### 📱 Responsive İyileştirmeler
- Mobil cihazlarda daha iyi kullanıcı deneyimi için layout düzenlemeleri
- Header ve navigasyon elemanlarının mobil optimizasyonu

### 📄 Dokümantasyon
- README.md güncellendi (sürüm v0.0.2 olarak işaretlendi)
- Gizlilik politikası (privacy.html) güncellendi
- Kullanım koşulları (terms.html) güncellendi
- İletişim sayfası (contact.html) güncellendi

### 🎯 Diğer İyileştirmeler
- CSS optimizasyonları ve kod temizliği
- Bileşen yapısında iyileştirmeler (`sidebar.js`, `note-list.js`)
- Genel performans iyileştirmeleri

---

## [v0.0.1] - İlk Sürüm

### ✨ Özellikler
- Yerel depolama (LocalStorage) ile %100 gizlilik
- Kategori sistemi ile not organizasyonu
- AES-GCM şifreleme ile güvenli yedekleme
- Responsive tasarım
- Çevrimdışı çalışma desteği
- Minimalist ve modern arayüz
