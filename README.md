# Trendyol tarzı Next.js mağaza

Türkçe, mobil uyumlu alışveriş arayüzü. Next.js App Router, React, Tailwind CSS ve Lucide ikonları kullanılır.

## Çalıştırma

```sh
npm install
npm run dev
```

Windows PowerShell betik kısıtlaması varsa `npm` yerine `npm.cmd` kullanın. Adres: http://localhost:3000

```sh
npm run build
npm start
```

Ürün arama, kategori filtreleme, fiyat sıralama, favoriler ve adet kontrollü sepet çalışır. Favoriler ve sepet localStorage ile tarayıcıda saklanır. Kategoriye ait örnek ürün yoksa boş sonuç ekranı gösterilir.

Bu bir ön yüz demosudur. Ürünler ve kampanyalar örnektir; ödeme, üyelik, satıcı ve sipariş servisi bağlı değildir. Fotoğraflar Unsplash, yazı tipleri Google Fonts üzerinden yüklenir ve internet bağlantısı gerektirir.

Next.js uygulaması `app/` dizinindedir. Sayfa ve Tailwind sınıfları `app/page.js`, kök düzen `app/layout.js` içindedir. `app/globals.css` yalnızca Tailwind girişini, yazı tiplerini ve ortak temel stilleri içerir. Tailwind, `postcss.config.mjs` üzerinden derlenir.

Kurulum: [Tailwind CSS resmi Next.js kılavuzu](https://tailwindcss.com/docs/installation/framework-guides/nextjs).
