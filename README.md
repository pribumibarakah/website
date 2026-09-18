# Laman Web Rasmi: Pribumi Baraqah Sdn. Bhd.

Laman web korporat satu halaman (*Single-Page Website*) untuk **Pribumi Baraqah Sdn. Bhd.** (No. Syarikat: 1322733-T).

## Maklumat Korporat & Pendaftaran

- **Nama Syarikat:** Pribumi Baraqah Sdn. Bhd.
- **No. Pendaftaran Syarikat (SSM):** 1322733-T
- **Kementerian Kewangan Malaysia (MOF):**
  - **No. Sijil:** K10085610793592160
  - **No. Rujukan Pendaftaran:** 357-0002364679
  - **Tempoh Sah Laku:** 07/08/2023 - 06/08/2026
  - **Status:** Berdaftar & Aktif (23 Kod Bidang Lampiran A)
  - **Individu Diberi Kuasa / Pengarah:** Encik Adryan Wong Hua De
- **Alamat Pejabat Operasi:**
  10-2, Binjai 8, Lorong Binjai, Kuala Lumpur, 50450 Kuala Lumpur, Wilayah Persekutuan Kuala Lumpur
- **Telefon / WhatsApp:** [011-8888 7268](https://wa.me/601188887268)

## Struktur Projek

```
website-2/
├── assets/
│   ├── css/
│   │   ├── bootstrap.min.css
│   │   ├── style.css
│   │   ├── custom.css       <-- Penggayaan tersuai bagi kad MOF, lencana & WhatsApp
│   │   └── ...
│   ├── js/
│   │   ├── custom.js        <-- Penapisan langsung 23 kod bidang MOF & borang WhatsApp
│   │   └── ...
│   └── img/
├── index.html               <-- Laman utama tunggal (Single Page)
└── README.md
```

## Ciri-Ciri Utama Laman Web

1. **Navigasi Satu Halaman (*Smooth Scroll*):**
   - Laman Utama (`#home`)
   - Profil Syarikat (`#about`)
   - Kelayakan & Sijil MOF (`#mof`)
   - Skop Perkhidmatan (`#services`)
   - Galeri Projek (`#projects`)
   - Hubungi & Lokasi Kami (`#contact`)
2. **Pameran Sijil & 23 Kod Bidang MOF:**
   - Carian pantas berinteraktif mengikut kod atau kata kunci perkhidmatan.
   - Penapisan kategori (Penyelenggaraan, Hiasan & Perabot, Kebersihan, ICT, Bekalan Am & Pakaian, Guna Tenaga).
3. **Integrasi Perhubungan Pantas:**
   - Butang WhatsApp terapung (*floating button*) ke nombor `011-8888 7268`.
   - Borang sebut harga dengan penghantaran mesej berformat terus ke WhatsApp.
   - Peta Google Maps ke Binjai 8 Kuala Lumpur.