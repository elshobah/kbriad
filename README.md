# KBRI Abu Dhabi – Portal Layanan Digital

Landing page konsep portal layanan digital KBRI Abu Dhabi. Desain modern, mobile-first, dengan tautan layanan, bahasa ganda, dan integrasi terjemahan otomatis.

## Fitur Utama
- Hero highlight layanan resmi KBRI Abu Dhabi.
- Kartu layanan (HaloAbuDhabi, Pelindungan WNI, Kekonsuleran, Pariwisata WNA, Investasi/Perdagangan, Hotline, Buku Saku PMI) yang bisa diklik; default membuka di tab baru.
- Switch bahasa (Indonesia, English, Arab) terhubung ke Google Translate widget.
- CTA “Mulai Layanan” pada layar non-mobile; disembunyikan otomatis di mobile.
- Tema gelap modern dengan grid responsif.

## Struktur
- `index.html` – seluruh markup dan styling inline, termasuk script terjemahan Google dan interaksi kartu.
- `LICENSE` – lisensi proyek.

## Cara Pakai
1) Buka `index.html` di browser modern.  
2) Klik tombol bahasa untuk mengaktifkan terjemahan otomatis.  
3) Klik kartu layanan untuk membuka tautan utama di tab baru; tautan di dalam kartu tetap berfungsi normal.

## Catatan
- Placeholder ikon/emoticon dapat diganti dengan ikon resmi atau set vektor sesuai kebutuhan.  
- Ganti URL pada `data-href` atau tautan di dalam kartu dengan endpoint produksi KBRI.  
- Logo dan favicon memakai aset resmi `logo-kbri-abu-dhabi.svg`/`.png` dari storage eksternal.  
- Terjemahan Google hanya dimuat saat halaman dibuka (client-side); pastikan koneksi internet tersedia.  
- Jika menambah skrip eksternal lain, pertahankan performa mobile-first dan hindari blokir rendering.

## Kredit
Dibuat oleh elshobah (elshobah.com) dan Tim KBRI Abu Dhabi.
