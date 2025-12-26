# FlowTime - Modern Pomodoro Timer

## 📋 Proje Hakkında

**FlowTime**, modern ve kullanıcı dostu bir Pomodoro zaman yönetimi uygulamasıdır. Bu uygulama ile üretkenliğinizi artırabilir, odaklanma sürelerinizi optimize edebilirsiniz.

## ✨ Özellikler

### 🎯 Timer Modları
- **Pomodoro Modu**: Klasik Pomodoro tekniği
- **Geri Sayım Modu**: Özel zaman ayarlı geri sayım
- **Kronometre Modu**: Süre ölçümü ve tur kaydı

### 📊 İstatistikler
- Tamamlanan seans takibi
- Toplam odaklanma süresi
- Günlük hedef takibi
- Günlük seri takibi

### ⚙️ Ayarlar
- Çalışma ve mola süreleri özelleştirme
- Uzun mola ayarları
- Seans sayısı yapılandırması

### 📱 Tasarım
- Modern ve koyu tema
- Responsive tasarım (mobil uyumlu)
- Animasyonlar ve geçiş efektleri
- Progress ring ile görsel geri bildirim

## 🚀 Kurulum ve Kullanım

### Gereksinimler
- Modern web tarayıcı
- İnternet bağlantısı (CDN'ler için)

### Yerel Kurulum
```bash
https://github.com/MustafaDevloper/FlowTime.git
cd flowtime
# Dosyayı herhangi bir web sunucusunda açın
```



## 🔧 API Entegrasyonu

### Firebase Entegrasyonu (İsteğe Bağlı)
```javascript
// Kendi Firebase konfigürasyonunuzu ekleyin:
const firebaseConfig = {
    apiKey: "BURAYA_KENDI_API_KEY_NIZI_EKLEYIN",
    authDomain: "BURAYA_AUTH_DOMAIN_EKLEYIN",
    projectId: "BURAYA_PROJE_ID_EKLEYIN",
    storageBucket: "BURAYA_STORAGE_BUCKET_EKLEYIN",
    messagingSenderId: "BURAYA_MESSAGING_SENDER_ID_EKLEYIN",
    appId: "BURAYA_APP_ID_EKLEYIN"
};
```

### AdSense Entegrasyonu (İsteğe Bağlı)
```html
<!-- Kendi AdSense kodunuzu ekleyin -->
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-BURAYA_CLIENT_ID_EKLEYIN" crossorigin="anonymous"></script>
```

## 📁 Dosya Yapısı

```
flowtime/
├── index.html          # Ana uygulama dosyası
├── README.md          # Bu dosya
```

## 🎨 Özelleştirme

### Renk Teması
```css
:root {
    --primary: #6366F1;        /* Ana renk */
    --primary-dark: #4F46E5;   /* Koyu ana renk */
    --accent: #10B981;         /* Vurgu rengi */
    --secondary: #F59E0B;      /* İkincil renk */
    --dark: #0F172A;           /* Koyu arkaplan */
    --light: #F8FAFC;          /* Açık metin */
}
```

### Timer Ayarları
- Varsayılan çalışma süresi: 25 dakika
- Varsayılan mola süresi: 5 dakika
- Varsayılan uzun mola: 15 dakika
- Seans başına tur: 4

## 📱 Responsive Özellikler

- **Masaüstü**: Tam ekran optimizasyonu
- **Tablet**: 768px altında uyumlu
- **Mobil**: 480px altında uyumlu
- **Touch dostu**: Büyük butonlar ve dokunmatik optimizasyon

## 🔒 Gizlilik ve Güvenlik

Bu demo versiyonunda:
- Kullanıcı verileri localStorage'da saklanır
- Firebase entegrasyonu devre dışıdır
- AdSense reklamları devre dışıdır
- Tüm dış bağlantılar demo amaçlıdır




## 🐛 Hata Raporlama

Hata bulursanız mustafaaydogan_official instagram adresinden bildiriniz

## ✨ Teşekkürler

- [Font Awesome](https://fontawesome.com) - İkonlar
- [Google Fonts](https://fonts.google.com) - Yazı tipleri
- [Firebase](https://firebase.google.com) - Backend servisleri (demo dışı)
- [AdSense](https://adsense.google.com) - Reklam platformu (demo dışı)

## 📞 İletişim

Proje Sahibi - [@mustafaaydogan_official](https://instagram.com/mustafaaydogan_official) 


