# Uwais Farm — Website Penjualan Domba Qurban & Aqiqah

Website statis (HTML + CSS) untuk katalog domba qurban dan aqiqah Uwais Farm. Pemesanan via WhatsApp.

## Struktur File

```
index.html          # Halaman utama (SEO meta, JSON-LD, konten)
style.css           # Styling
robots.txt          # Aturan crawler + lokasi sitemap
sitemap.xml         # Sitemap
site.webmanifest    # Web app manifest
images/             # Gambar teknis hasil optimasi (WebP + JPG, ikon, og-image)
```

## SEO

- Title, meta description, canonical, Open Graph, Twitter Card
- JSON-LD: LocalBusiness, WebSite, ItemList/Product, FAQPage, BreadcrumbList
- Satu `<h1>`, heading berurutan, landmark semantik, alt text deskriptif
- `robots.txt` dan `sitemap.xml`

Jika domain berubah, ganti `https://mra2194.github.io/Uwais-Farm/` di `index.html`, `robots.txt`, dan `sitemap.xml`.

## Publish ke GitHub Pages

Settings > Pages > Branch `main`, folder `/ (root)` > Save.
