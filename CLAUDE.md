# projeteklif-site (proje özeti)

> Son güncelleme: 2026-11-18 (ilk sürüm: tanıtım, gizlilik, destek)

https://projeteklif.app sitesinin yayın deposu (herkese açık). Cloudflare Pages `projeteklif-site` projesi `public/`
klasörünü yayınlar; **`main`'e push = otomatik yayın**. Derleme adımı yok, düz HTML.

- `public/index.html`: tanıtım sayfası (koyu açılış bandı, iki telefon; üç adım; proje okuma, kendi fiyatın, teklif, hızlı hesap;
  iPhone, Duo, iPad, Android; gizlilik özeti; Pro (yakında); diğer uygulamalarımız).
- `public/site.css`: ortak stil; renkler uygulamanın `src/theme/tema.css` dosyasından. Yazı tipi Plus Jakarta Sans (`public/fonts/`, OFL);
  Google Fonts isteği yok. Koyu tema var.
- `public/gizlilik/`, `public/destek/`: gizlilik politikası ve destek (mağaza gizlilik ve destek URL'leri). DWG dönüşümü metni uygulama
  deposundaki `server/dwg/README.md` ile aynı kalmalı (dosya hemen silinir, günlükte ad/içerik/IP yok, IP yalnızca bellekte 10 dk).
- `public/ekran/`: ekran görüntüleri (WebP), **yalnızca örnek veriyle** (uygulama deposunda `VITE_ORNEK=1` derlemesi,
  `src/data/ornekVeri.ts`). Gerçek müşteri projesi, eğitim projesi ya da gerçek fiyat listesi asla konmaz.
- `public/og.png` paylaşım görseli, `apple-touch-icon.png`, `icon-192/512.png`, `logo.svg` (uygulamanın `src/theme/logo.svg`), `robots.txt`, `sitemap.xml`.
- `public/apps/`: "Diğer uygulamalarımız" simgeleri (128 px). Yeni uygulama yayınlanınca buraya ve kardeş sitelere eklenir.
  Projeteklif mağazalarda yayınlanınca kardeş sitelere de eklenir.
- Hiçbir firma adı, logosu ya da firma sitesine bağlantı bu sitede geçmez (uygulama kuralı).

Uygulama deposu: `mahsunse-maker/projeteklif` (özel, `~/Desktop/projeteklif`). Uyarı: Pages projesini asla o özel depoya bağlama.

Proje listesi: `~/.claude/CLAUDE.md`.
