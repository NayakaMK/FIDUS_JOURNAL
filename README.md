# 🪐 FIDUS AI — Smart CBT Tele-Counseling & Mental Health Monitoring

> **Proyek IPTEK / Inovasi Digital - Universitas Brawijaya** > Sebuah purwarupa platform kesehatan mental berbasis Kecerdasan Buatan (AI) terintegrasi untuk mendeteksi dini stres akademis, otomatisasi pencatatan jurnal kognitif (CBT), serta sistem pemantauan krisis mahasiswa secara *real-time* oleh konselor ahli.

---

## 駐 Latar Belakang & Masalah
Banyak mahasiswa mengalami tekanan akademis namun enggan mencari bantuan profesional karena stigma atau keterbatasan akses. Di sisi lain, metode penulisan jurnal terapi perilaku kognitif (CBT) manual sering kali tidak konsisten dilakukan. **FIDUS AI** hadir sebagai *first-line support* berbasis sahabat sebaya cerdas yang mampu mengonversi obrolan kasual mahasiswa menjadi metrik klinis terstruktur.

## ✨ Fitur Utama (Core Features)
* **AI Cognitive Behavioral Therapy (CBT) Companion:** Konselor sebaya bertenaga Gemini API yang berempati tinggi, menghindari *toxic positivity*, dan mampu mengarahkan pengguna merefleksikan emosinya secara terapeutik.
* **Automated Clinical Journal Extraction:** Setiap sesi obrolan dianalisis secara gaib oleh backend untuk mengekstrak sentimen skor ($0 - 1000$), domain stres (akademis, sosial, finansial, dll), taktik koping, serta rangkuman jurnal harian ke dalam database secara otomatis.
* **Real-time Counselor Crisis Dashboard:** Fitur *monitoring* otomatis bagi dokter/psikiater UB Wellness Center. Jika sistem mendeteksi mahasiswa dengan tingkat sentimen di bawah ambang batas krisis, notifikasi siaga darurat akan langsung muncul di dashboard dokter untuk intervensi langsung.
* **Integrated Wellness Rooms:** Ruang relaksasi mandiri yang menyediakan latihan pernapasan taktis (Metode 4-7-8) disertai *ambient soundscape* serta tantangan interaktif *Grounding Focus* (5-4-3-2-1) dengan *mock-smile engagement tracker*.

---

## 📐 Arsitektur Sistem & Teknologi
Aplikasi ini dikembangkan dengan arsitektur **Stateless Frontend - Monolithic Backend** yang efisien untuk kebutuhan prototipe cepat skala tinggi.

* **Frontend:** HTML5, CSS3, JavaScript Vanilla, Bootstrap v5.3 (Midnight Blue Glassmorphic Theme), Chart.js.
* **Backend:** Node.js, Express.js, CORS.
* **Artificial Intelligence:** Google Generative AI Cloud SDK (Gemini Pro Engine) dengan teknik *Advanced System Instruction* & *JSON Structured Response Parsing*.
* **Database:** MySQL (Relational Pooling System).

---

## 🚀 Panduan Instalasi & Menjalankan Aplikasi

Ikuti langkah-langkah di bawah ini untuk menjalankan *environment* FIDUS AI di komputer lokal Anda:

### 1. Prasyarat (Prerequisites)
Pastikan komputer Anda sudah terinstal:
* **Node.js** (Versi 18 ke atas direkomendasikan)
* **XAMPP / MySQL Server**

### 2. Kloning Repositori
```bash
git clone [https://github.com/username-kamu/nama-repo-lomba.git](https://github.com/username-kamu/nama-repo-lomba.git)
cd nama-repo-lomba
