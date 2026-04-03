# ⚽ HalıSaha Pro

Arkadaş grupları için tam özellikli halı saha yönetim uygulaması.  
Tek HTML dosyası — sunucu gerekmez, GitHub Pages üzerinde çalışır.

🔗 **Canlı Demo:** `https://KULLANICI_ADIN.github.io/halisaha/`

---

## 🚀 Özellikler

### 🏟 Saha Görünümü
- 3D perspektifli halı saha
- Gerçekçi SVG futbolcu formaları
- Kaleci için ayrı renk
- 10 farklı dizilim seçeneği (GK·1-2, GK·2-1, GK·1-2-1, GK·2-2 …)
- Doğru köşe çeyrek daireleri
- 3D kale görünümü

### 📋 Maç Organizasyonu (5 Adım)
1. **Maç Bilgisi** — Saha, gün, tarih, saat, format
2. **Davet Gönder** — Seçilen oyunculara WhatsApp'tan davet linki
3. **Katılım Takibi** — Oyuncular linke tıklar, katılıp katılamayacaklarını bildirir
4. **Kadro Kur** — Katılanları sürükle-bırak ile takımlara dağıt
5. **Kadro Gönder** — Her oyuncuya kişiselleştirilmiş WhatsApp mesajı

### ⚙️ Kurulum
- Takım adı ve rengi özelleştirme
- Kaleci rengi ayrı seçimi
- Sürükle-bırak oyuncu dağılımı
- Otomatik rastgele dağıtma

### 👥 Oyuncular
- Manuel oyuncu ekleme
- Telefon rehberinden ekleme (Android Chrome)
- WhatsApp numarası kaydetme

### 🏆 Turnuva Modu
- 4 veya 8 takımlı eleme turnuvası
- Skor girişi ve otomatik kazanan belirleme
- Tur atlama ve şampiyon ilanı

---

## 📦 GitHub Pages'e Yükleme

### 1. Repository Oluştur
```
GitHub.com → New repository → "halisaha" → Public → Create
```

### 2. Dosyaları Yükle
Repo sayfasında `Add file → Upload files` ile şunları yükle:
- `index.html`
- `README.md`

### 3. GitHub Pages Aktif Et
```
Settings → Pages → Source: Deploy from branch → Branch: main → / (root) → Save
```

### 4. URL'yi Al
Birkaç dakika sonra:
```
https://KULLANICI_ADIN.github.io/halisaha/
```

---

## 🔑 Yetkili Girişi

Varsayılan şifre: **1234**

Yetkili özellikleri:
- Maç oluşturma ve organizasyon
- Oyuncu ekleme/silme
- Takım kurma ve kadro gönderme
- Turnuva oluşturma

---

## 📱 Davet Linki Nasıl Çalışır?

1. Organizatör **Organizasyon** sekmesinden maç oluşturur
2. Oyuncuları seçip **Davet Gönder**'e basar
3. WhatsApp açılır, her oyuncuya link gönderilir
4. Oyuncu linke tıklar → uygulama açılır → adını seçer → ✅/❌ butonuna basar → WhatsApp'ta cevap mesajı otomatik hazırlanır
5. Organizatör katılımcı listesini görür ve takımları kurar

> **Not:** Davet linkinin çalışması için uygulama **GitHub Pages'te yayında** olmalıdır.

---

## 🛠 Teknik Detaylar

- Tek dosya HTML/CSS/JS (framework yok)
- `localStorage` ile veri kalıcılığı
- Contact Picker API (Android Chrome rehber erişimi)
- WhatsApp `wa.me` deep link entegrasyonu
- SVG sahası ve formalar
