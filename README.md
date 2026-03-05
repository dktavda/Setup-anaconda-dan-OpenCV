# Laporan Praktikum 1: Konfigurasi Infrastruktur Computer Vision
Mata Kuliah: Machine Learning  
Dosen: Herfandi, A.Md., S.Kom., M.Kom

---

## Identitas Mahasiswa
- **Nama:** Dinda Oktavia Pratiwi
- **NIM:** 231001026
- **Topik:** Setup Environment & Library Pengenalan Dasar

### Arsitektur Environment:
- **Platform:** Anaconda CLI (Command Line Interface)
- **Interpreter:** Python 3.11
- **Package Source:** Conda-forge & PyPI
- **Dependency Utama:** OpenCV-Python

### Langkah-Langkah Praktik Setup Environment:
Berikut adalah rangkuman prosedur teknis yang telah saya lakukan:
1. **Membuat Virtual Environment:**  
   `agar sistem isolasi terjaga dan menghindari konflik library:
conda create -n ENV_BELAJAR_4 python=3.11`
2. **Mengaktifkan Environment:**  
   `untuk mulai bekerja di ruang isolasi yang telah dibuat:
conda activate ENV_BELAJAR_4`
3. **Menginstal library OpenCV:**  
   `melalui repositori Conda-forge (yang merupakan "Play Store"-nya library bagi pengembang):
pip install opencv-python`
4. **Melakukan Verifikasi Instalasi:** 
    `melalui Anaconda Prompt untuk memastikan library terpasang secara sempurna tanpa ada kendala file DLL (Import Success).`

## Analisis & Verifikasi Kode
Verifikasi dilakukan melalui skrip `main.py` dengan logika sebagai berikut:
- **Modul `cv2`**: Melakukan import library OpenCV ke kernel aktif.
- **Fungsi `__version__`**: Mengecek validitas instalasi dan kompatibilitas versi yang terpasang.

## Link Video Youtube
Dokumentasi visual mengenai proses setup dan analisis mendalam dapat diakses melalui:
[**Presentasi Video YouTube**](https://youtu.be/q3OmQDZA88w?si=gyGyIdyxddAQi8a5)
