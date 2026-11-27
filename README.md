# IKANESIA

Platform identifikasi dan informasi ikan lokal Indonesia.
_Satu Foto, Kenali Kekayaan Ikan Nusantara._

## Menjalankan

```bash
npm install
npm run dev      # http://localhost:5173
npm run build    # hasil build di dist/
```

## Stack
React 19 · Vite · Tailwind CSS v4 · React Router DOM · Lucide React

## Struktur
- `src/components` — Navbar, Footer, Button, Container, SectionHeading, Logo, dll.
- `src/pages` — halaman per rute
- `src/layouts` — kerangka halaman (Navbar + konten + Footer)
- `src/data` — data statis (identitas situs, navigasi)
- `src/hooks`, `src/utils`, `src/assets`

Token desain (warna, font, bayangan) ada di `src/index.css` pada blok `@theme`.
Lihat contohnya di rute `/design-system`.
