# Root Governance: Rust-WASM-UI-Lab

Dokumen ini memuat aturan tingkat root untuk monorepo **Rust WASM UI Lab**.

## Prinsip Aturan Berjenjang

Aturan hanya berlaku **di level folder tempat aturan itu berada** dan **tidak mengatur isi yang lebih dalam**.

- **Root**: hanya mengatur isi di root.
- **Rak**: aturan hanya berlaku untuk isi di rak tersebut.
- **Sub-Rack (SR)**: kontainer utama untuk Buku.
- **Buku**: aturan hanya berlaku untuk isi di buku tersebut.

## Struktur Root

- `README.md` sebagai pendahuluan singkat (Taxonomy & Matrix).
- `.cursorrules` sebagai hukum interaksi AI.
- `docs/` untuk dokumentasi pendukung.
- `RAK-xx-.../` sebagai kumpulan rak (domain/tema).

## Konvensi Penomoran

- **Rak**: `RAK-01`, `RAK-02`, ...
- **Sub-Rack**: `SR-01`, `SR-02`, ...
- **Buku**: `BK-01`, `BK-02`, ...
- **Bab**: `CH-01`, `CH-02`, ...

## Ruang Lingkup Root

- Konvensi penamaan folder di root.
- Struktur folder tingkat root.
- Prinsip aturan berjenjang.
- Konvensi penomoran & AI Persona.

## Status

Aktif. Mematuhi Gold Standard PPM V4.
