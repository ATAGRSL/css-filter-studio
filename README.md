# 🎨 CSS Filter Studio

[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://html.spec.whatwg.org/)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://www.w3.org/Style/CSS/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ATAGRSL/css-filter-studio)

> **Modern, güçlü ve kullanıcı dostu CSS filtreleme uygulaması** - Resimler üzerinde profesyonel efektler uygulayabileceğiniz gelişmiş bir fotoğraf düzenleme platformu.

Bu uygulama, **7 farklı CSS filtresi** ve **4 transformasyon efekti** ile resimler üzerinde gerçek zamanlı düzenleme yapmanızı sağlar. Glassmorphism tasarım, responsive yapı ve Türkçe arayüzü ile kullanıcı deneyimini üst düzeye çıkarır.

## 🌟 Proje Amacı

Bu proje, web teknolojilerinin gücünü kullanarak tarayıcıda çalışan bir fotoğraf düzenleme uygulaması geliştirmek amacıyla oluşturulmuştur. Amacımız:

- ✅ Modern CSS özelliklerini pratikte göstermek
- ✅ Web API'lerinin kullanımını öğretmek
- ✅ Responsive ve erişilebilir tasarım prensipleri uygulamak
- ✅ Performans odaklı kod yazımını sergilemek

## 🚀 Özellikler

### 🎨 Gelişmiş Filtre Kontrolleri
- **7 farklı CSS filtre türü**:
  - Parlaklık (Brightness): 0-200%
  - Kontrast (Contrast): 0-200%
  - Doygunluk (Saturate): 0-300%
  - Siyah-Beyaz (Grayscale): 0-100%
  - Sepya (Sepia): 0-100%
  - Bulanıklık (Blur): 0-20px
  - Renk Döndürme (Hue-rotate): 0-360°

### 🔄 Transformasyon Kontrolleri
- **4 farklı dönüşüm efekti**:
  - Döndürme (Rotate): -180° to +180°
  - Ölçeklendirme (Scale): 50% to 200%
  - Eğme X (Skew X): -45° to +45°
  - Eğme Y (Skew Y): -45° to +45°

### 🖼️ Filtre Ön Ayarları
- **8 hazır filtre**:
  - Siyah-Beyaz
  - Sepya
  - Bulanık
  - Kontrast
  - Canlı (parlaklık + doygunluk)
  - Renk Değiştir (hue-rotate)
  - Negatif (invert)
  - Doygun (saturate)

### 📷 Resim Yükleme Seçenekleri
- **Dosya seçici**: PNG, JPG, GIF formatları
- **Sürükle & Bırak**: Resimleri sürükleyip bırakarak yükleme
- **Webcam desteği**: Canlı kamera ile fotoğraf çekme
- **Gerçek zamanlı önizleme**: Yüklenen resim anında görüntülenir

### 🔄 Gelişmiş İşlevsellik
- **Sürükle & Bırak**: Resimleri sürükleyip bırakarak yükleme
- **Geri Al / İleri Al**: Filtre geçmişini yönetme (Ctrl+Z / Ctrl+Y)
- **CSS Kopyalama**: Uygulanan filtreleri CSS kodu olarak kopyalama
- **Resim Kaydetme**: Filtrelenmiş resmi PNG formatında kaydetme (Ctrl+S)
- **Geçmiş Yönetimi**: Tüm filtreleme adımlarını takip etme
- **Gerçek zamanlı önizleme**: Değişiklikler anında görüntülenir

### ⌨️ Klavye Kısayolları
- `Ctrl/Cmd + Z`: Geri Al
- `Ctrl/Cmd + Y`: İleri Al
- `Ctrl/Cmd + S`: Resmi Kaydet
- `ESC`: Modal pencereleri kapat

### 💾 Veri Kalıcılığı
- **LocalStorage entegrasyonu**: Filtre ayarları ve geçmiş tarayıcıda saklanır
- **Oturum kurtarma**: Sayfa yenilendiğinde son durum geri yüklenir
- **Otomatik kaydetme**: Her değişiklik otomatik olarak kaydedilir

### 📱 Responsive Tasarım
- **Mobil uyumlu**: Tüm cihazlarda mükemmel çalışır
- **Modern UI/UX**: Glassmorphism efekti, gradient'ler, animasyonlar
- **Erişilebilirlik**: Klavye navigasyonu ve screen reader desteği

## 🛠️ Kullanım

### 1. **Resim Yükleme**
- **Dosya seçici**: Sol üst köşedeki "📷 Resim Yükle" butonuna tıklayın
- **Sürükle & Bırak**: Resimleri doğrudan yükleme alanına sürükleyin
- **Webcam**: "Webcam Kullan" butonuna tıklayarak kamera ile fotoğraf çekin
- **Desteklenen formatlar**: PNG, JPG, GIF

### 2. **Filtre Uygulama**
- **Ön ayarlar**: Sol paneldeki hazır filtre butonlarından seçim yapın
- **Manuel kontrol**: Slider'ları kullanarak her filtreyi ayrı ayrı ayarlayın
- **Kombinasyon**: Birden fazla filtreyi aynı anda uygulayabilirsiniz
- **Transformasyon**: Döndürme, ölçeklendirme ve eğme efektlerini kullanın

### 3. **İşlem Yapma**
- **Geri Al / İleri Al**: Sol paneldeki butonları veya klavye kısayollarını kullanın
- **CSS Kopyala**: Uygulanan filtreleri CSS kodu olarak panoya kopyalayın
- **Resim Kaydet**: Filtrelenmiş resmi PNG formatında bilgisayarınıza kaydedin
- **Geçmiş**: Tüm yaptığınız değişiklikleri geçmiş panelinden görüntüleyin

## 🎯 Teknik Detaylar

### CSS Filtreleri ve Transformasyonlar

#### **CSS Filtreleri**:
- `brightness(0%-200%)`: Parlaklık kontrolü
- `contrast(0%-200%)`: Kontrast ayarı
- `saturate(0%-300%)`: Renk doygunluğu
- `grayscale(0%-100%)`: Siyah-beyaz efekt
- `sepia(0%-100%)`: Sepya tonu
- `blur(0px-20px)`: Bulanıklık efekti
- `hue-rotate(0deg-360deg)`: Renk dönüşümü
- `invert(100%)`: Negatif efekt (ön ayarlarda)

#### **CSS Transformasyonları**:
- `rotate(-180deg to 180deg)`: Döndürme
- `scale(50%-200%)`: Ölçeklendirme
- `skewX(-45deg to 45deg)`: X ekseninde eğme
- `skewY(-45deg to 45deg)`: Y ekseninde eğme

### Dosya Yapısı
```
/
├── index.html          # Ana uygulama dosyası (HTML + CSS + JavaScript)
└── README.md           # Proje dokümantasyonu
```

### Kullanılan Teknolojiler
- **HTML5**: Semantic markup ve modern API'ler
- **CSS3**: Modern layout (Grid, Flexbox), animations, backdrop-filter
- **ES6+ JavaScript**: Classes, async/await, arrow functions, destructuring
- **Canvas API**: Resim işleme ve kaydetme
- **MediaDevices API**: Webcam erişimi
- **LocalStorage API**: Veri kalıcılığı
- **Font Awesome 6**: İkonlar

### Tarayıcı Desteği
- **Modern tarayıcılar**: Chrome 80+, Firefox 75+, Safari 13+, Edge 80+
- **ES6+ özellikler**: Classes, Promises, async/await
- **CSS modern özellikler**: Grid, Flexbox, backdrop-filter, CSS transforms
- **Web API'leri**: Canvas 2D, MediaDevices, LocalStorage, Clipboard API

### Performans Özellikleri
- **Gerçek zamanlı rendering**: Değişiklikler anında uygulanır
- **Optimized canvas operations**: Verimli resim işleme
- **Lazy loading**: Resimler sadece gerekli olduğunda yüklenir
- **Memory management**: Webcam stream'leri otomatik temizlenir

## 🚀 Çalıştırma

### Yerel Sunucu ile (Önerilen)
```bash
# Python 3.x
python -m http.server 8000

# Python 2.x
python -m SimpleHTTPServer 8000

# Node.js (http-server paketi ile)
npx http-server

# PHP
php -S localhost:8000
```

### Doğrudan Tarayıcıda
1. `index.html` dosyasını bulun
2. Dosyaya çift tıklayın veya tarayıcınıza sürükleyin
3. Uygulama açılacak ve kullanıma hazır olacak

> **Not**: Webcam özelliğini kullanabilmek için HTTPS gereklidir. Yerel sunucu kullanırken HTTPS protokolü kullanılmalıdır.



### 📋 **Sistem Gereksinimleri**
- **Web Tarayıcı**: Modern web tarayıcısı (Chrome 80+, Firefox 75+, Safari 13+, Edge 80+)
- **JavaScript**: ES6+ desteği
- **CSS**: CSS3, Grid, Flexbox desteği
- **Web API'leri**: Canvas 2D, MediaDevices, LocalStorage, Clipboard API
- **Network**: Webcam kullanımı için HTTPS bağlantısı

### ⚡ **Hızlı Başlangıç**
1. Repository'yi klonlayın
2. `index.html` dosyasını tarayıcınızda açın
3. Hemen kullanmaya başlayın! 🚀

## 🎨 Tasarım Özellikleri

### UI/UX Tasarımı
- **Glassmorphism tasarım**: Modern, şeffaf cam efekti
- **Gradient backgrounds**: Çoklu renk geçişleri ve dinamik arka planlar
- **Smooth animasyonlar**: CSS transitions ve keyframe animasyonları
- **Interactive hover states**: Buton ve element hover efektleri
- **Modern typography**: Okunaklı font hiyerarşisi
- **Professional color palette**: Tutarlı renk şeması

### Responsive Design
- **Mobile-first approach**: Mobil cihazlar için optimize edilmiş
- **Tablet uyumluluk**: Orta boy ekranlarda mükemmel görünüm
- **Desktop optimizasyon**: Geniş ekranlarda tam özellik desteği
- **Touch-friendly**: Dokunmatik ekranlarda kullanım kolaylığı
- **Progressive enhancement**: Özellik tespiti ile uyumluluk

### Erişilebilirlik
- **Keyboard navigation**: Klavye ile tam navigasyon desteği
- **Screen reader friendly**: ARIA etiketleri ve semantic HTML
- **High contrast**: Yeterli renk kontrastı
- **Focus indicators**: Klavye odak göstergeleri

## 🐛 Sorun Giderme

### Yaygın Problemler
1. **Webcam çalışmıyor**
   - HTTPS bağlantısı kullandığınızdan emin olun
   - Tarayıcı izinlerini kontrol edin
   - Başka bir tarayıcı deneyin

2. **Resim yüklenmiyor**
   - Desteklenen formatları kontrol edin (PNG, JPG, GIF)
   - Dosya boyutunun çok büyük olmadığını kontrol edin
   - Tarayıcı konsolunu inceleyin

3. **Filtreler uygulanmıyor**
   - Resmin yüklendiğinden emin olun
   - Tarayıcı konsolunda JavaScript hatalarını kontrol edin
   - Sayfayı yeniden yükleyin

### Hata Ayıklama
```javascript
// Tarayıcı konsolunda debug bilgilerini görmek için
console.log('FilterStudio initialized');
console.log('Current filters:', this.currentFilters);
console.log('Current transforms:', this.currentTransforms);
```

## 📝 Lisans

Bu proje **MIT Lisansı** altında lisanslanmıştır.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Bu lisans şunları yapmanıza izin verir:
- ✅ **Ticari Kullanım**: Projeyi ticari projelerinizde kullanabilirsiniz
- ✅ **Değişiklik**: Kaynak kodunda istediğiniz değişiklikleri yapabilirsiniz
- ✅ **Dağıtım**: Değiştirilmiş versiyonları dağıtabilirsiniz
- ✅ **Özel Kullanım**: Kişisel projelerinizde kullanabilirsiniz
- ✅ **Sınırsız**: Herhangi bir kısıtlama olmadan kullanabilirsiniz

### 📋 **Lisans Koşulları**
- Orijinal lisans ve telif hakkı bildirimini korumak
- Herhangi bir garanti veya sorumluluk kabul etmemek
- Lisans metnini projenizle birlikte dağıtmak

### 🔗 **Lisans Detayları**
Tam lisans metni için: [LICENSE](LICENSE) dosyasına bakın veya [MIT License](https://opensource.org/licenses/MIT) sayfasını ziyaret edin.

## 🤝 Katkıda Bulunma

Katkıda bulunmak isteyenler için:

### Geliştirme Ortamı
1. **Fork** edin: https://github.com/ATAGRSL/css-filter-studio
2. **Clone** edin: `git clone https://github.com/ATAGRSL/css-filter-studio.git`
3. **Branch** oluşturun: `git checkout -b feature/AmazingFeature`
4. **Değişiklik** yapın ve test edin
5. **Commit** edin: `git commit -m 'Add some AmazingFeature'`
6. **Push** edin: `git push origin feature/AmazingFeature`
7. **Pull Request** açın

### Kod Kalitesi
- ES6+ JavaScript standartlarını kullanın
- JSDoc yorumları ekleyin
- Responsive design prensiplerini takip edin
- Erişilebilirlik (accessibility) kurallarına uyun
- Performans optimizasyonlarına dikkat edin

### Test Etme
- Farklı tarayıcılarda test edin (Chrome, Firefox, Safari, Edge)
- Mobil cihazlarda test edin
- Klavye navigasyonunu test edin
- WebCam özelliklerini test edin

## 📊 Proje İstatistikleri

### 📈 **Kod Metrikleri**
- **Toplam Kod Satırları**: ~1,900+ satır
- **HTML**: ~1,900 satır (ana uygulama)
- **CSS**: ~1,000+ satır (içsel CSS)
- **JavaScript**: ~400+ satır (FilterStudio sınıfı)

### 🎯 **Özellik Sayıları**
- **CSS Filtreleri**: 7 farklı tip (brightness, contrast, saturate, grayscale, sepia, blur, hue-rotate)
- **Transform Efektleri**: 4 farklı tip (rotate, scale, skewX, skewY)
- **Ön Ayar Filtreler**: 8 hazır filtre kombinasyonu
- **JavaScript Fonksiyonları**: 20+ metod
- **Responsive Breakpoint**: 3 farklı ekran boyutu (desktop, tablet, mobile)

### 🎨 **UI/UX Metrikleri**
- **Renk Paleti**: 15+ CSS değişkeni
- **Animasyonlar**: 10+ CSS keyframe ve transition efekti
- **İkonlar**: Font Awesome 6 ikon seti
- **Typography**: Responsive font scale sistemi

### 📱 **Tarayıcı Desteği**
- **Chrome**: 80+ ✅
- **Firefox**: 75+ ✅
- **Safari**: 13+ ✅
- **Edge**: 80+ ✅

## 🎯 Gelecek Özellikler

Planlanan geliştirmeler:
- [ ] Daha fazla CSS filtre desteği
- [ ] Batch resim işleme
- [ ] Filtre şablonları kaydetme/yükleme
- [ ] Sosyal medya paylaşım entegrasyonu
- [ ] Resim sıkıştırma optimizasyonu
- [ ] Dark/Light tema desteği
- [ ] Çoklu dil desteği

---

## 👨‍💻 Geliştirici

### 👤 **Ata Gürsel**
**Full-Stack Web Developer & UI/UX Enthusiast**

**GitHub**: https://github.com/ATAGRSL  
**LinkedIn**: https://www.linkedin.com/in/atagursel/  


### 💼 **Hakkımda**
Modern web teknolojileri ile kullanıcı dostu ve performanslı uygulamalar geliştiriyorum. CSS, JavaScript ve UI/UX tasarım konularına özel ilgi duyuyorum.

### 🎯 **Bu Projedeki Rolüm**
- 🎨 **UI/UX Tasarım**: Glassmorphism tasarım ve responsive yapı
- 💻 **Frontend Development**: HTML5, CSS3, ES6+ JavaScript
- 🔧 **Web API Entegrasyonu**: Canvas, MediaDevices, LocalStorage
- 📱 **Mobil Optimizasyon**: Cross-platform uyumluluk
- 📚 **Dokümantasyon**: Detaylı README ve kod yorumları

---

## 🙏 Teşekkürler

Bu projeyi kullanmanız ve ilgilenmeniz için teşekkür ederim! Proje geliştirme sürecinde kullandığım teknolojilere ve kaynaklara minnettarım:

### 🛠️ **Kullanılan Teknolojiler**
- **Font Awesome**: İkonlar için
- **Google Fonts**: Tipografi için
- **Modern Web Browsers**: Test ve uyumluluk için

### 📚 **Kaynaklar**
- **MDN Web Docs**: Web API referansları
- **CSS-Tricks**: CSS teknikler ve ipuçları
- **W3C Specifications**: Web standartları

### ⭐ **Destek**
Eğer bu proje hoşunuza gittiyse, lütfen GitHub'da **yıldız** vermeyi unutmayın! Bu, projenin daha fazla geliştirici tarafından keşfedilmesine yardımcı olacaktır.

---