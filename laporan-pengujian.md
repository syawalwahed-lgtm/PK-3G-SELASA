# Laporan Pengujian — Pendidikan Kesihatan Tahun 3

## Status sebenar
**Status:** Pemeriksaan kod statik dan semakan struktur kandungan telah dibuat ketika penjanaan. Ujian hujung-ke-hujung dalam pelayar sebenar, pada peranti fizikal dan pada GitHub Pages belum dijalankan dalam sesi ini. Oleh itu, laporan ini tidak mendakwa aplikasi telah lulus ujian runtime penuh.

## Pemeriksaan yang dibuat pada fail sumber
- [x] Fail `index.html` dihasilkan dengan HTML, CSS dan JavaScript dalam satu fail.
- [x] Bank soalan mempunyai tepat 25 entri data; setiap satu mempunyai empat pilihan, indeks jawapan betul dan penerangan.
- [x] Aliran halaman merangkumi halaman utama, nota, video, dua permainan, kuiz, laporan dan panduan keselamatan.
- [x] Formula peratus ditetapkan sebagai `Math.round(markah / 25 * 100)`.
- [x] Fungsi cetak menggunakan `window.print()` dan CSS cetakan.
- [x] Audio mempunyai kawalan hidup/mati dan fallback senyap jika SpeechSynthesis/Web Audio tidak tersedia.
- [x] Simpanan setempat menggunakan `localStorage` dalam pelayar jika dibenarkan.
- [x] Penetapan semula dan percubaan semula meminta pengesahan.

## Ujian manual yang masih perlu dibuat
Jalankan pada sekurang-kurangnya satu komputer dan satu telefon/tablet:
1. Masukkan nama, mula pembelajaran, navigasi nota ke depan/belakang.
2. Buka video YouTube; sahkan pilihan pautan terus dan alternatif tanpa video.
3. Lengkapkan semua 5 situasi permainan pertama dan 5 situasi permainan kedua.
4. Jawab kesemua 25 soalan, cuba jawapan salah dan fungsi “Cuba lagi”, semak markah dan pastikan tiada markah berganda.
5. Sahkan markah 25/25 menghasilkan 100%, lencana dan lima bintang; uji juga 0/25 dan skor pertengahan.
6. Cuba audio dengan peranti menyokong dan tidak menyokong SpeechSynthesis.
7. Cuba muat semula pelayar dan sahkan kemajuan setempat.
8. Uji percubaan semula dan tetapan semula dengan serta tanpa pengesahan.
9. Cetak laporan ke PDF dan semak pemotongan halaman.
10. Semak responsif pada lebar 320 px, telefon biasa, tablet dan desktop; semak papan kekunci dan pembaca skrin asas.
11. Jika diterbitkan ke GitHub Pages, uji pautan HTTPS sebenar dan fungsi selepas deployment.

## Batasan dan risiko
- Video memerlukan internet; sesetengah sekolah mungkin menyekat YouTube atau kandungan terbenam.
- Penyimpanan setempat bergantung pada tetapan pelayar; mod private atau sekatan storan boleh menghalangnya.
- Bunyi/pertuturan bergantung pada keupayaan peranti dan pelayar.
- Pemetaan kurikulum perlu disemak oleh guru terhadap DSKP/RPT rasmi terkini sekolah.
