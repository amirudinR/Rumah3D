# Rumah 3D — 6 × 10 m

Simulator 3D + RAB interaktif rumah 6 × 10 m (60 m²) dengan dak beton siap lantai 2, mengikuti PDF `Desain Rumah 6x10 m Dak Siap Lantai 2.pdf`.

## Pakai

Buka `index.html` dengan double-click. Tidak perlu build/server. Three.js diambil dari CDN, jadi butuh internet.

- Slider progres 0–100% = lantai 1, 100–200% = lantai 2.
- Slider harga besi/semen/umum/upah untuk simulasi kenaikan harga.
- Tombol **Atas** untuk melihat denah dari atas, **Bongkar beton** untuk tulangan, **Dimensi** untuk ukuran.

## Denah (sesuai PDF 6x10)

| Ruang | Ukuran | Luas |
|---|---|---|
| R. tamu | 3,50 × 3,50 | 12,25 m² |
| Dapur | 2,50 × 3,50 | 8,75 m² |
| R. keluarga + makan | 4,50 × 3,00 | 13,50 m² |
| KM luar | 1,50 × 1,80 | 2,70 m² |
| R. cuci / gudang | 1,50 × 1,20 | 1,80 m² |
| KT 1 (anak) | 3,00 × 3,50 | 10,50 m² |
| KT 2 (utama) | 3,00 × 3,50 | 10,50 m² |
| KM dalam (di KT 2) | 1,50 × 1,40 | 2,10 m² |
| **Total** | 6,00 × 10,00 | **60 m²** |
| Teras + kanopi dak | 6,00 × 1,50 | 9 m² (di luar 60 m²) |

Urutan dari depan: R. tamu + dapur → R. keluarga + KM luar + R. cuci → KT 1 + KT 2.

## Struktur

- Grid kolom 3,0 × 3,5 / 3,0 / 3,5 m, **12 footplat** 100×100×25.
- Kolom 20/20 (8 D12), sloof 20/30 (4 D12, 32 m), balok dak 15/30 (32 m).
- Plat dak 12 cm D10-150 dua lapis, kemiringan 1% ke belakang, **dicor penuh**.
- Rencana tangga ke lantai 2 (0,90 × 2,60) hanya digambar putus-putus, belum dibangun.

## Biaya (harga pasar Okt 2026)

| | |
|---|---|
| Subtotal | **Rp 236.118.500** |
| Cadangan 10% | Rp 23.611.850 |
| **Total lantai 1** | **Rp 259.730.350** |
| Per m² | Rp 4.328.839 |
| Tahap 1 (pondasi → dak) | Rp 148.046.300 |
| Tahap 2 (finishing) | Rp 111.684.051 |
| Lantai 2 (perkiraan) | ± Rp 265.000.000 |

PDF 6x10 memberi ± Rp 267,1 juta untuk 60 m² — angka di atas sejalan (selisih karena harga satuan lebih baru).
Ongkos kirim material, tanah, PBG, sambungan PLN, pagar, dan perabot **tidak termasuk**.

> Konsep awal — wajib dicek arsitek & ahli struktur sebelum dibangun.
