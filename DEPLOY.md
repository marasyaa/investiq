# InvestIQ PWA — GitHub Pages Deploy Kılavuzu

## Klasör Yapısı
```
investiq-pwa/
├── index.html       ← Ana uygulama
├── manifest.json    ← PWA kimliği
├── sw.js            ← Service Worker (offline)
└── icons/
    ├── icon-192.svg
    └── icon-512.svg
```

## GitHub Pages'e Deploy

### 1. Yeni repo oluştur
```
Repo adı: investiq  (veya istediğin ad)
Visibility: Public
```

### 2. Dosyaları yükle
```bash
git init
git add .
git commit -m "Initial InvestIQ PWA"
git remote add origin https://github.com/KULLANICI_ADIN/investiq.git
git push -u origin main
```

### 3. GitHub Pages aktive et
```
Settings → Pages → Source: Deploy from branch
Branch: main / (root)
Save
```

### 4. Erişim URL'si
```
https://KULLANICI_ADIN.github.io/investiq/
```

## PWA Kurulumu (Kullanıcı Tarafı)
- **Chrome/Edge masaüstü:** Adres çubuğunda sağdaki "Yükle" ikonuna tıkla
- **Android Chrome:** "Ana ekrana ekle" bildirimi çıkar
- **iOS Safari:** Paylaş → "Ana Ekrana Ekle"

## Sonraki Adım: Adım 2
Analiz Motoru eklenecek:
- 20+ rasyo hesaplama
- DuPont ayrıştırması  
- DCF modeli
- Güven skoru (0-100)
- Trafik ışığı karar sistemi
