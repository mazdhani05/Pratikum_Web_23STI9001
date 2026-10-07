# 🎮 Game Localization Specialist - Portofolio Praktikum

Repositori ini dibuat untuk memenuhi tugas praktikum **Branding Personal & Lokalisasi Produk Digital**. Di sini saya mendemonstrasikan proses lokalisasi teks game dari Bahasa Inggris (EN) ke Bahasa Indonesia (ID) dengan fokus pada aspek kultural, imersi pemain, dan batasan teknis UI game.

---

## 👤 Profil & Positioning
* **Nama:** Ramandhani
* **Peran:** Game Localization Specialist / Game L10n Tester
* **Fokus:** Mengadaptasi teks game (Dialog, UI, Item, & Skill) agar terasa natural bagi komunitas gamer di Indonesia tanpa menghilangkan esensi mekanik game aslinya.

---

## ⚔️ Studi Kasus: Lokalisasi Game RPG Fantasi (Simulasi)

**Deskripsi Proyek:**  
Melokalkan elemen teks dari sebuah game RPG fantasi agar dialognya terdengar epik namun akrab di telinga gamer Indonesia, serta memastikan teks deskripsi muat di dalam kotak menu (*UI Box*).

### 📊 Tabel Analisis Lokalisasi Game

| Elemen Game | Teks Asli (EN) | Terjemahan Kaku (Mesin) | Hasil Lokalisasi (ID) | Analisis Kultural & Teknis UI |
| :--- | :--- | :--- | :--- | :--- |
| **System UI** | *You perished! Respawn in {time}s.* | Anda binasa! Hidup kembali di {time}s. | **Kamu Gugur! Bangkit dalam {time}dtk.** | Mengubah *Anda binasa* menjadi *Kamu Gugur* agar terasa lebih epik khas game RPG. Variabel `{time}` wajib dipertahankan agar kode game tidak rusak. |
| **Nama Item** | *Health Potion* | Ramuan Kesehatan | **Ramuan Pemulih HP** | Di kalangan gamer Indonesia, istilah *HP (Health Points)* jauh lebih populer dan natural dibanding kata *Kesehatan*. |
| **Deskripsi Skill** | *Deals 50 DMG and stuns the enemy for 2s.* | Menangani 50 DMG dan mengejutkan musuh selama 2 detik. | **Berikan 50 DMG dan efek stun pada musuh selama 2 dtk.** | Kata *stun* (pingsan/kaku) dipertahankan sebagai jargon game yang sudah umum, dan kata *detik* disingkat *dtk* agar muat di kotak deskripsi skill. |
| **Dialog NPC** | *Wha... What a drag. Fine, I'll help you.* | Apa... Apa seret. Bagus, aku akan membantumu. | **Hah... Merepotkan sekali. Ya sudah, aku bantu.** | Menyelamatkan idiom *What a drag* (ekspresi malas khas karakter anime/game) menjadi kalimat kasual yang natural bagi audiens lokal. |

---

## 🛠️ Kompetensi Teknis Game L10n yang Ditunjukkan

1. **Variables Handling:** Paham cara menjaga variabel kode game seperti `{time}`, `{player_name}`, atau `\n` (baris baru) agar teks tidak *error* saat di-render oleh sistem game.
2. **Glossary & Consistency:** Menjaga konsistensi penerjemahan istilah game (seperti mengubah *Gold* menjadi *Koin*, atau *Quest* menjadi *Misi*) dari awal hingga akhir.
3. **Structured Format (JSON):** Menyediakan berkas terjemahan dalam format `.json` yang siap diintegrasikan langsung oleh developer ke dalam game engine (Unity/Unreal).

---
*Catatan: Proyek ini bersifat simulasi untuk kepentingan akademis/praktikum.*
