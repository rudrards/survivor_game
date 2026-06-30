# 🛡️ Survivor — Terra Cordia

Karanlık kapıların ardındaki gerçeği keşfet. 10 karakter, 6 bölge, gerçek zamanlı kule savunması ve online skor tablosu içeren bir hayatta kalma oyunu.

## 🎮 Oynamak için

[BURAYA OYNANABILIR LİNKİ EKLE — GitHub Pages aktif edince]

Veya `index.html` dosyasını herhangi bir tarayıcıda aç.

## 📲 Uygulama olarak yükle (PWA)

1. Oyunu mobil tarayıcıda aç
2. "Ana ekrana ekle" / "Uygulama olarak yükle" bildirimini onayla
3. Artık uygulama gibi tam ekran çalışır, internet olmadan da açılır

## ⚔️ Karakterler

Rudengan, Niheyrs, Rova, Novir, Null, Zhou, Rayan, Gabriel, Chan, ve Kral Valerius Thorne — her birinin kendine özel silahları, ultimate yetenekleri ve hikayesi var.

## 🌍 Bölgeler

Orman Kapısı, Zindan Kapısı, Cehennem Kapısı, Gökyüzü Kapısı, Buz Alanı, Unutulmuş Şehir.

## 🏰 Ekstra Mod

Ana menüden ayrı bir Kule Savunması mini oyunu mevcut.

## 🔒 Teknik Notlar

Bu proje tek bir `index.html` dosyasında çalışan saf HTML/CSS/JavaScript ile yazılmıştır — herhangi bir build aracı veya sunucu gerektirmez.

Online skor tablosu Supabase üzerinden çalışır. Skor tablosunda kullanılan API anahtarı bilinçli olarak herkese açık (anon/publishable) bir anahtardır — front-end uygulamalarda bu normaldir, gerçek güvenlik Supabase tarafındaki Row Level Security (RLS) politikalarıyla sağlanır. Bu projede:
- ✅ Skor silme tamamen kapalı
- ✅ İstemci tarafında rate-limiting ve değer doğrulama var
- ✅ Hiçbir ödeme/para sistemi yok
- ✅ Hiçbir kişisel veri toplanmıyor (sadece oyuncu adı ve skor)

## 📜 Lisans

Kişisel proje — tüm hakları saklıdır.
