# Isı Pompası Kapasite Hesabı

Saha servis teknisyenleri için geliştirilmiş mobil uyumlu hesaplama aracı.

## Özellikler

- **Anlık Kapasite** — Debi + ΔT → kW (veya herhangi bir değeri boş bırak, hesaplasın)
- **Tank / Boyler** — Hacim + sıcaklık + süre → kW / süre hesabı
- **COP Analizi** — Gerçek cihaz tablosundan DB × LWT interpolasyonu, voltaj/akım analizi
- **PWA** — Telefona yüklenebilir, offline çalışır

## Kullanım

Uygulamayı doğrudan şu adresten açın:  
👉 `https://KULLANICI_ADIN.github.io/isi-pompasi-hesap/isi_pompasi_hesap.html`

Telefonda **"Ana Ekrana Ekle"** seçeneğiyle uygulama gibi kullanılabilir.

## Dosyalar

| Dosya | Açıklama |
|---|---|
| `isi_pompasi_hesap.html` | Ana uygulama |
| `manifest.json` | PWA manifest |
| `sw.js` | Service worker (offline destek) |
| `icon-192.png` | Uygulama ikonu (192px) |
| `icon-512.png` | Uygulama ikonu (512px) |
