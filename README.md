# Laporan Riset Kecil: Evaluasi Teknik Renang Gaya Bebas Berbasis Pose Estimation

## 1. Rencana Topik yang Dipilih
Sistem Evaluasi dan Analisis Koreksi Teknik Renang Gaya Bebas (Freestyle) Berbasis Web Menggunakan Pose Estimation (MediaPipe Pose) dan Rule-Based Reasoning.

## 2. Formulasi Masalah
* Bagaimana mengekstraksi koordinat sendi tubuh (keypoints) dari video renang gaya bebas menggunakan algoritma Pose Estimation di tengah tantangan pembiasan air?
* Bagaimana merumuskan aturan geometri biomekanika (rule-based) untuk mendeteksi kesalahan sudut siku (recovery) dan sudut lutut (kick) pada renang gaya bebas?

## 3. Riset Gap dari Penelitian Terdahulu
* Sebagian besar penelitian pose estimation di bidang olahraga berfokus pada aktivitas darat (seperti push-up, squat, atau yoga) yang memiliki latar belakang stabil dan tanpa hambatan media air.
* Penelitian sports analytics untuk renang yang sudah ada umumnya berbasis perangkat keras (wearable sensor bernilai mahal) atau sebatas klasifikasi gaya renang tanpa memberikan penjelasan (feedback) titik kesalahan gerakan secara spesifik.

## 4. Peluang Pengembangan
* Mengembangkan sistem berbasis web tanpa sensor tambahan (camera-only) yang mampu menganalisis sudut sendi secara real-time atau dari rekaman video.
* Menerapkan aturan biomekanika berbasis pengetahuan domain (domain knowledge) dari pelatih/atlet renang untuk menghasilkan umpan balik visual yang mendidik dan terjangkau bagi masyarakat umum.

## 5. Sumber Dataset, Kode, dan Referensi Jurnal

### a. Nama Repository Dataset Riset
* Swimming Style / Pose Dataset (Kaggle / SwimTrack Dataset)

### b. Alamat GitHub / Kaggle
* Dataset & Pre-trained Model: https://github.com/google/mediapipe (MediaPipe Pose Solutions)
* Dataset: https://drive.google.com/drive/folders/1tTh05eal8v5CkxBG_yai5jKxq9-_FGoL?usp=sharing

### c. Referensi Jurnal
1. Lugalia, R., et al. "Human Pose Estimation for Swimming Stroke Analysis Using Computer Vision." Journal of Sports Science and Technology.
2. Bazarevsky, V., et al. (2020). "BlazePose: On-device Real-time Body Pose Tracking." arXiv preprint arXiv:2006.10204.
