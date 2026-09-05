# 📝 Kuis Master — Ubah Soal Jadi Kuis

Aplikasi web yang mengubah kumpulan soal pilihan ganda menjadi **kuis interaktif** — cukup tulis atau tempel soalmu, tekan satu tombol, dan langsung main. Ringan, tanpa server, tanpa instalasi.

## ✨ Fitur

- ⚡ **Parser soal otomatis** — ubah teks soal menjadi kuis dalam sekejap
- 🖊️ **Format fleksibel** — dukung penanda jawaban `*` maupun baris `Jawaban: B`
- 🤖 **Mode Lawan Bot** — adu skor melawan bot (3 tingkat: Santai/Seimbang/Jenius) dengan papan skor VS langsung
- 🔥 **Penyemarak** — penghitung rentetan (streak), animasi poin melayang, efek suara kombo & jingle kemenangan
- 🎮 **Kuis interaktif** — satu soal per layar, progress bar, dan navigasi maju/mundur
- ✅ **Umpan balik langsung** — tahu benar/salah begitu memilih (bisa dimatikan)
- 🔀 **Acak soal & pilihan** — cegah hafalan urutan
- ⏱️ **Batas waktu per soal** — mode tantangan opsional
- 📊 **Skor & pembahasan** — lihat nilai akhir plus kunci jawaban tiap soal
- 🧬 **Bank soal bawaan** — 6 bank siap main satu klik: 75 soal Protein, 85 soal Karbohidrat, 90 soal Bioenergetika/Siklus Krebs/Fosforilasi Oksidatif, 100 soal Metabolisme Lipid, 100 soal Pondasi Biokimiawi, & 100 soal Membran Sel
- 🔊 **Backsound & efek suara** — musik latar lembut plus bunyi benar/salah/selesai (Web Audio, tanpa file eksternal, bisa dimatikan)
- 🎉 **Efek konfeti** — perayaan saat nilaimu tinggi
- 💾 **Tersimpan otomatis** — soal & pengaturan disimpan di browser (localStorage)
- 📱 **Responsif** — nyaman di HP maupun desktop

## 🚀 Cara Menjalankan

Cukup buka `index.html` di browser apa pun:

```bash
# Langsung buka file, atau jalankan server lokal:
python3 -m http.server 8000
# lalu buka http://localhost:8000
```

## 🧑‍🏫 Cara Pakai

1. Buka tab **Buat Soal**, tulis atau tempel soalmu (atau tekan **Isi Contoh**).
2. Tekan **⚡ Ubah Jadi Kuis** — soal diperiksa dan pratinjau ditampilkan.
3. Buka tab **Mainkan**, tekan **🚀 Mulai Kuis**.
4. Jawab tiap soal, lalu lihat skor dan pembahasan di akhir.

## ✍️ Format Soal

Tandai jawaban benar dengan tanda bintang `*`:

```
1. Ibu kota Indonesia adalah...
A. Bandung
B. Jakarta*
C. Surabaya
D. Medan
```

Atau pakai baris kunci jawaban:

```
Siapa presiden pertama Indonesia?
A. Soeharto
B. Soekarno
C. Habibie
Jawaban: B
```

Catatan format:
- Nomor soal (`1.`, `2.`) boleh ada atau tidak.
- Label pilihan boleh `A.`, `A)`, `a.`, `1.`, dsb.
- Pisahkan tiap soal dengan **satu baris kosong**.
- Minimal 2 pilihan per soal, satu ditandai sebagai jawaban benar.

## 🛠️ Teknologi

HTML, CSS, dan JavaScript murni dalam satu file — tanpa framework, tanpa dependensi, tanpa build step.
