# Döngü – Web Sitesi

Döngü'nün tanıtım sitesi: giyilmeyen kıyafetleri öğrencilere ve iyilik butiklerine ulaştıran döngüsel moda altyapısı.

## Yapı

- `index.html` – ana sayfa (tek dosya, statik HTML)
- `assets/` – WebP ürün/kampanya görselleri, logo, favicon, paylaşım görseli ve tanıtım videosu
- `vercel.json` – Vercel ayarları

Derleme adımı yoktur; Vercel dosyaları doğrudan yayınlar. `main` dalına yapılan her push otomatik olarak yayına alınır.

## Yer tutucular

Köşeli parantez içindeki alanlar (`[ÜNİVERSİTE]`, `[FİYAT]`, `[ADET]`, `[E-POSTA]` vb.) gerçek bilgilerle doldurulmalıdır.

## Açık işler

- Pilot formu henüz bir yere veri göndermiyor (doğrulama ve bilgilendirme mesajı var).
- Sık sorulanlar ve KVKK aydınlatma metni sayfaları hazırlanmalı.
- `og:image` mutlak adres olmalı; kalıcı alan adı belli olunca güncellenmeli.
- Ürün fotoğraflarının bir kısmı marka görselleri; herkese açık yayından önce gerçek bağış fotoğraflarıyla değiştirilmeli.

## Güvenlik

Güvenlik başlıkları (CSP, nosniff, frame-ancestors) `vercel.json` içinde tanımlıdır. `.env` dosyaları `.gitignore` ile dışarıda tutulur; anahtar/şifre depoya eklenmemelidir.
