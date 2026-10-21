# 🌳 Sesi 6: Attributing Direct Drivers to Deforestation Alerts with Satellite Imagery & AI

Proyek ini berisi Executive Dashboard & Interactive Simulator berbasis web untuk studi kasus pemantauan perubahan hutan tropis, deteksi *deforestation alerts*, serta klasifikasi atribusi driver langsung menggunakan citra satelit dan kecerdasan buatan (*Artificial Intelligence*). Materi ini disusun berdasarkan kuliah praktisi internasional oleh **Dr. Bart Slaughter** (Postdoctoral Researcher in Remote Sensing, Wageningen University and Research / WUR, Belanda).

---

## 📌 Ringkasan Studi Kasus

Hutan tropis dunia mengalami deforestasi cepat yang dipicu oleh berbagai aktivitas manusia maupun gangguan alam. Pemantauan modern menggunakan satelit memungkinkan deteksi perubahan tutupan pohon secara mingguan pada skala piksel 10 hingga 30 meter.

Aplikasi web ini menyajikan:
- **Perbandingan Sentinel-1 (Radar) vs Sentinel-2 (Optical)**: Keunggulan citra optik untuk kesehatan vegetasi vs kemampuan radar menembus awan (*cloud-free*) di wilayah tropis.
- **Atribusi 4 Driver Utama Kehilangan Hutan**:
  1. *Agriculture*: Pembukaan lahan perkebunan skala kecil dan besar (berdasarkan ukuran dan indikasi api).
  2. *Resource Extraction*: Aktivitas pertambangan emas ilegal dan pembukaan jalan tebangan kayu selektif (*selective logging*).
  3. *Wildfires*: Kebakaran hutan musiman yang dipicu oleh kekeringan ekstrem (misalnya di Bolivia, Amazon, dan Kalimantan).
  4. *Natural Disturbances*: Kerusakan alami akibat banjir di sepanjang sungai atau angin badai besar (*windthrows*).
- **Deep Learning Model (CNN)**: Penggunaan *Convolutional Neural Network* yang memproses tumpukan citra (*multiband image stack*) secara otomatis setiap bulan.
- **Global Nature Watch**: Publikasi data terbuka untuk meningkatkan transparansi tata kelola hutan.

---

## 🚀 Fitur Utama Web Dashboard

- **Executive Forestry Metrics**: Ringkasan indikator frekuensi deteksi alerts, model AI utama, keunggulan radar, dan platform global.
- **Direct Drivers Showcase**: Kartu interaktif penjelasan 4 pendorong utama kerusakan hutan beserta tantangan akurasinya.
- **Kalkulator Evaluasi Performa Model AI**: Simulator interaktif berbasis Alpine.js untuk menguji perbandingan *Overall Accuracy* (yang sering didominasi kelas mayoritas agrikultur) melawan *Micro F1-Score* (evaluasi seimbang untuk kelas minoritas seperti pertambangan dan bencana alam).

---

## 🛠️ Teknologi yang Digunakan

- **HTML5 & Tailwind CSS**: Tampilan antarmuka modern, responsif, dan rapi.
- **Alpine.js**: Komponen interaktif untuk simulator evaluasi model AI.
- **FontAwesome**: Ikon visual yang intuitif.

---

## 💻 Cara Menjalankan Aplikasi

1. Unduh atau *clone* repositori ini:
   ```bash
   git clone [https://github.com/aprilizzaa/Sesi-6.-Attributing-Direct-Drivers-to-Deforestation-Alerts-with-Satellite-Imagery-and-AI.git](https://github.com/aprilizzaa/Sesi-6.-Attributing-Direct-Drivers-to-Deforestation-Alerts-with-Satellite-Imagery-and-AI.git)
