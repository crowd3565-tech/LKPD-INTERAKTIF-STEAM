# LKPD Interaktif STEAM — Ekosfer Botol

Lembar Kerja Peserta Didik interaktif untuk **Biologi Fase E (Kelas X), Kurikulum Merdeka**, materi **Ekosistem**, dengan model PjBL-STEAM.

Proyek: siswa merancang ekosistem air tawar tertutup di dalam botol (ekosfer), lalu mengamatinya selama 14 hari.

| Unsur | Aktivitas |
|---|---|
| **S**cience | Klasifikasi biotik/abiotik, peran organisme, penyusun jaring makanan interaktif, pola interaksi (umpan balik otomatis) |
| **T**echnology | Simulasi predator–mangsa Lotka–Volterra (RK4) dengan pengatur parameter, daya dukung, dan peristiwa panen; pemilihan alat ukur |
| **E**ngineering | Siklus desain rekayasa: Tanya → Bayangkan → Rencanakan → Buat → Uji → Perbaiki, dengan peringatan rancangan otomatis |
| **A**rt | Kanvas sketsa penampang ekosfer, rancangan poster kampanye |
| **M**athematics | Piramida energi (aturan 10%), logbook 14 hari + grafik, estimasi populasi Lincoln–Petersen |

Fitur lain: simpan otomatis (localStorage), skor otomatis, ringkasan jawaban siap salin untuk dikirim ke guru, panduan guru (alur, kunci, rubrik), mode gelap, dan tampilan ponsel.

## Cara pakai
Satu berkas `index.html` tanpa instalasi. Buka langsung di peramban, atau aktifkan **GitHub Pages** (Settings → Pages → branch `master`, folder `/`) agar siswa bisa mengakses lewat tautan.

---

# Eco-Explorer — LKPD Digital Interaktif (`eco-explorer.html`)

Petualangan Menjelajahi Ekosistem. Website 15 halaman bergaya pixel-art berdasarkan storyboard PjBL-STEAM.

| Bagian | Halaman | Fitur |
|---|---|---|
| I · Pembukaan | 1–4 | Sampul animasi, identitas & anggota kelompok, peta perjalanan belajar, adegan kolam yang dapat diklik |
| II · Eksplorasi | 5–9 | Drag-and-drop biotik/abiotik & peran organisme, kuis, mencocokkan interaksi, menyusun rantai makanan, jaring-jaring makanan, simulasi populasi, piramida ekologi + kalkulator 10% |
| III · Investigasi STEAM | 10–13 | Pilih lokasi & checklist, rancang bingkai kuadrat (pratinjau + luas otomatis), tabel data dengan kepadatan/frekuensi/KR otomatis, unggah foto, kanvas peta ekosistem dengan stiker |
| IV · Evaluasi | 14–15 | Kuis 15 soal (PG, B/S, menjodohkan, kasus) dengan skor & pembahasan, refleksi, evaluasi kelompok, unduh laporan .html / cetak PDF |

Pengaturan guru (nama guru, sekolah, tautan video) ada di objek `CONFIG` di awal `<script>`.
Jawaban tersimpan di peramban perangkat siswa (localStorage). Siswa mengirim hasil lewat tombol **Unduh laporan** di halaman 15.
