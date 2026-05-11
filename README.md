# English-Mastery
# 📚 English Mastery

**Roadmap belajar bahasa Inggris berbasis kurikulum internasional (CEFR & Cambridge English) — dari A1 Beginner sampai C1 Advanced. Satu file HTML, langsung jalan di browser, tanpa server, tanpa instalasi.**

![English Mastery Screenshot](https://img.shields.io/badge/version-3.0-blue) ![License](https://img.shields.io/badge/license-MIT-green) ![No Dependencies](https://img.shields.io/badge/dependencies-none-brightgreen) ![CEFR](https://img.shields.io/badge/standard-CEFR%20%2F%20Cambridge-orange)

---

## 🌟 Tentang Proyek

English Mastery adalah aplikasi web single-file yang dirancang sebagai **personal learning tracker** untuk belajar bahasa Inggris secara sistematis. Kurikulum disusun berdasarkan standar internasional — **Common European Framework of Reference (CEFR)** dan **Cambridge English Curriculum** — mencakup 144+ topik grammar, pronunciation, vocabulary, dan skill dari level A1 hingga C1.

Proyek ini dibuat dengan semangat **belajar mandiri yang terstruktur**: tidak hanya daftar topik random, tapi roadmap yang jelas dengan detail apa yang harus dipelajari, contoh kalimat, dan rekomendasi sumber belajar terpercaya.

---

## ✨ Fitur

### 📖 Kurikulum Lengkap (144+ Topik)
- **6 level CEFR**: A1 · A2 · B1 · B1+ · B2 · C1
- Setiap topik berisi: deskripsi, poin belajar, contoh kalimat (EN + ID), dan link sumber
- Sumber referensi: British Council, Cambridge Grammar in Use, Test-English.com, BBC Learning English

### ✅ Progress Tracker
- Centang topik yang sudah dipelajari — tersimpan otomatis di browser (localStorage)
- Progress bar per level + ring chart keseluruhan di dashboard
- Filter: tampilkan semua / belum selesai / sudah selesai
- Filter per CEFR level (A1–C1)

### 🖨️ Print Report
- Cetak laporan progress ke PDF atau printer
- Filter per level sebelum print
- Copy ke clipboard dalam format teks untuk WhatsApp / Notion

### 📖 Vocabulary Harian (Oxford 3000/5000)
- Word list Oxford 3000/5000 tertanam langsung — **tanpa API key, tanpa biaya**
- Definisi real-time dari [Free Dictionary API](https://dictionaryapi.dev/) (gratis, open source)
- Setiap kata: pengucapan IPA, 🔊 audio, part of speech, makna, contoh kalimat, sinonim/antonim
- **Streaming UX**: kartu muncul satu per satu seiring data masuk
- Pilih level (A1–C1) untuk kata yang sesuai kemampuan

### ⭐ Vocab Saved List
- Simpan kata favorit dengan tombol ★
- Tab "Vocab List" tersendiri: filter level, search, delete per kata, hapus semua
- Data tersimpan di browser — persisten antar sesi

### 🛠️ Admin Mode
- Tombol Mode Admin di header — aktifkan untuk unlock fitur edit
- **Edit** topik yang ada (nama, deskripsi, poin belajar, contoh, sumber)
- **Tambah** topik baru ke kategori mana pun
- **Tambah** kategori baru ke level mana pun
- **Tambah** level baru (untuk C2 atau topik custom)
- **Hapus** topik / kategori / level dengan konfirmasi
- Semua perubahan tersimpan di localStorage

---

## 🚀 Cara Pakai

### Opsi 1 — Download & Buka Langsung
```bash
# Clone repo
git clone https://github.com/username/english-mastery.git

# Buka file di browser
open english-mastery-final.html
# atau double-click file-nya
```

### Opsi 2 — Langsung dari GitHub Pages
Buka: `https://username.github.io/english-mastery/`

### Opsi 3 — Pakai Sekarang (tanpa download)
Download `english-mastery-final.html` → buka di browser manapun. Selesai.

---

## 📋 Struktur Kurikulum

| Level | Deskripsi | Jumlah Topik | Setara |
|-------|-----------|:---:|--------|
| **A1** | Beginner | 28 | Cambridge Starters · SD Kelas 1–3 |
| **A2** | Elementary | 27 | Cambridge Key (KET) · SD Kelas 4–6 |
| **B1** | Intermediate | 36 | Cambridge Preliminary (PET) · SMP |
| **B1+** | Upper-Intermediate | 16 | Pre-FCE · Transisi B2 |
| **B2** | Pre-Advanced | 27 | Cambridge First (FCE) · SMA |
| **C1** | Advanced | 14 | Cambridge Advanced (CAE) · Profesional |

### Kategori yang dicakup per level:
- **Tenses & Aspect** — semua tenses dari present simple sampai mixed conditionals
- **Modal Verbs** — can, could, must, should, might, will, would, dan nuance-nya
- **Passive Voice** — semua bentuk termasuk causative dan reporting passive
- **Conditionals** — Type 0/1/2/3, mixed, inversions, alternatives
- **Reported Speech** — statements, questions, commands, reporting verbs
- **Relative & Participle Clauses** — defining, non-defining, advanced forms
- **Gerunds & Infinitives** — semua patterns termasuk perfect & passive forms
- **Articles & Determiners** — a/an/the/Ø, quantifiers, pronouns
- **Adjectives & Adverbs** — comparison, order, position, -ed/-ing
- **Discourse & Linking** — coherence, emphasis, inversion, cleft sentences
- **Pronunciation & Skills** — phonics, connected speech, reading, writing, speaking, listening

---

## 🔧 Teknologi

| Komponen | Detail |
|----------|--------|
| **Stack** | Vanilla HTML + CSS + JavaScript — zero dependencies |
| **Storage** | `localStorage` — data 100% lokal di browser pengguna |
| **Vocabulary API** | [Free Dictionary API](https://dictionaryapi.dev/) — gratis, tanpa key |
| **Word List** | Oxford 3000/5000 (embedded, by CEFR level) |
| **Font** | DM Serif Display + DM Sans + DM Mono (Google Fonts) |
| **File Size** | ±176 KB (single HTML file) |
| **Browser Support** | Chrome, Firefox, Safari, Edge (modern versions) |

---

## 📁 Struktur File

```
english-mastery/
├── english-mastery-final.html   # Aplikasi utama — satu file ini saja yang diperlukan
├── README.md                    # Dokumentasi ini
└── LICENSE                      # MIT License
```

Tidak ada folder `node_modules`, tidak ada `package.json`, tidak ada build process. Buka file HTML → langsung jalan.

---

## 🗺️ Roadmap

Fitur yang direncanakan untuk versi berikutnya:

- [ ] **Flashcard mode** — latihan recall untuk setiap topik grammar
- [ ] **Spaced repetition** untuk vocabulary saved list
- [ ] **Quiz per topik** — soal multiple choice setelah mempelajari setiap topik
- [ ] **Export data** ke JSON (backup/restore progress)
- [ ] **Dark/light mode toggle**
- [ ] **PWA support** — install sebagai app di mobile
- [ ] **C2 level** — Mastery level topics

---

## 🤝 Kontribusi

Pull request sangat welcome! Beberapa area yang bisa dibantu:

- Tambah topik grammar yang belum tercakup
- Perbaiki atau tambah contoh kalimat
- Tambah terjemahan Indonesia yang belum ada di vocab hints
- Perbaiki bug atau improve UI/UX
- Tambah sumber belajar yang relevan

### Cara berkontribusi:
1. Fork repo ini
2. Buat branch baru: `git checkout -b fitur-baru`
3. Edit `english-mastery-final.html`
4. Commit: `git commit -m 'Tambah: deskripsi perubahan'`
5. Push & buat Pull Request

---

## 📜 Lisensi

MIT License — bebas dipakai, dimodifikasi, dan didistribusikan. Lihat file [LICENSE](LICENSE).

---

## 🙏 Kredit & Referensi

Kurikulum disusun berdasarkan sumber-sumber berikut:

- [Cambridge English Curriculum](https://www.cambridgeenglish.org) — standar dan level CEFR
- [British Council Learn English](https://learnenglish.britishcouncil.org) — grammar reference
- [Test-English.com](https://test-english.com) — grammar points per level
- [Oxford Learner's Dictionaries](https://www.oxfordlearnersdictionaries.com) — Oxford 3000/5000 word lists
- [Free Dictionary API](https://dictionaryapi.dev/) — definisi dan audio kata (open source)
- Cambridge Grammar in Use series (Murphy, R.) — struktur grammar

---

## 📬 Kontak

Dibuat dengan ☕ dan semangat belajar.

Kalau ada pertanyaan, saran, atau menemukan bug — buka [Issue](https://github.com/username/english-mastery/issues) di GitHub.

---

*English Mastery — Belajar Inggris dari nol sampai mahir, satu topik dalam satu waktu.*
