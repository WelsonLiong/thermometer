# Jom Teroka Suhu!

Website pembelajaran matematik interaktif dalam Bahasa Melayu. Dibina semula daripada satu skrin Interactive Thermometer di Maths Is Fun untuk tugasan Klinik Reka Semula Skrin Multimedia.

## Buka untuk pembentangan

Buka `dist/index.html` dalam browser. Semua fon, ilustrasi dan fungsi disimpan dalam folder ini; tiada pemasangan atau internet diperlukan untuk salinan tempatan. Kekalkan folder `assets`, `style.css` dan `app.js` bersama fail HTML.

Untuk pratonton melalui pelayan: jalankan `node server.cjs` dan buka http://127.0.0.1:4187. Versi hosted baharu diterbitkan sebagai private melalui Sites; pautan tidak memberi akses kepada ahli kumpulan secara automatik.

## Aliran

1. Ramal arah perubahan daripada suhu rujukan.
2. Laraskan suhu kepada sasaran. Seret terus cecair dalam termometer; perubahan dibundarkan kepada 1°C; tanda kecil pada termometer ialah 5°C.
3. Semak dan baca maklum balas khusus.
4. Jawab soalan kefahaman sebelum bergerak ke misi seterusnya.

Tiga misi: 10 → 30°C, 20 → 0°C, 30 → 20°C. Teroka bebas menyokong −10 hingga 50°C. Fahrenheit ialah pilihan tambahan. Bunyi dimatikan secara lalai; boleh dihidupkan. Papan kekunci: fokus termometer dan gunakan anak panah, Home atau End.

## Bahan tugasan

Lihat `LAPORAN.md` untuk pemetaan prinsip, protokol think-aloud dan rasional 150 patah perkataan. Bukti asal di folder induk `audit-termometer`, screenshot baharu di `.impeccable/review`. Tiada ujian sebenar bersama murid telah dijalankan.

## Aset

Ilustrasi asli dihasilkan dengan built-in ImageGen; prompt penuh direkodkan dalam `dist/assets/scenes.png.json`. Fredoka dan Nunito diambil daripada Google Fonts, berlesen SIL Open Font License. Sumber: https://github.com/google/fonts/tree/main/ofl/fredoka dan https://github.com/google/fonts/tree/main/ofl/nunito. Ikon SVG dan termometer ialah grafik geometri yang ditulis untuk prototaip ini.

Kemas kini: bahagian butang −/+, suhu contoh dan arahan berulang di bawah alat telah dibuang. Cursor tangan terbuka menunjukkan cecair boleh diseret; cursor menggenggam muncul ketika seretan. Kekunci anak panah, PageUp/PageDown dan Home/End kekal sebagai alternatif.
