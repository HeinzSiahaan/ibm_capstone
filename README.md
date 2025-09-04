# Financial Insight Dashboard with AI-Powered Code Generation

## Project Overview
Proyek ini bertujuan untuk membangun **dashboard analitik keuangan interaktif** yang dapat membantu pengguna dalam memahami tren pendapatan, risiko finansial, serta membuat interpretasi data secara lebih cepat dan akurat.  
Tujuan proyek sangat jelas, dengan latar belakang kuat terkait kebutuhan otomasi analisis keuangan. Permasalahan yang diselesaikan adalah **kurangnya fleksibilitas dalam mengolah data keuangan secara real-time**.  
Pendekatan dilakukan dengan menggabungkan pemrograman Python, visualisasi data, serta dukungan AI generatif untuk mempercepat pembuatan kode analisis.

## Technologies Used
- **Python**: Bahasa pemrograman utama untuk analisis data dan pengembangan aplikasi.
- **Streamlit**: Framework untuk membuat dashboard web interaktif dengan cepat.
- **Pandas & NumPy**: Digunakan untuk manipulasi data dan perhitungan numerik.
- **Matplotlib & Seaborn**: Visualisasi tren keuangan.
- **IBM Granite AI (Generative AI)**: Membantu menghasilkan kode Python secara otomatis berdasarkan prompt yang diberikan.
- **Jupyter Notebook**: Lingkungan utama untuk eksperimen dan dokumentasi analisis.

Alasan pemilihan teknologi:
- **Streamlit** dipilih karena kemudahan deployment dan kemampuan interaktif.
- **IBM Granite AI** dipilih karena mendukung **code generation** berbasis prompt, sehingga mempercepat pengembangan analisis dan meminimalisir kesalahan sintaks.

## Features
1. **Ringkasan Keuangan**: Menyajikan gambaran umum data finansial.
2. **Visualisasi Tren Pendapatan**: Menampilkan grafik interaktif untuk memantau pertumbuhan pendapatan.
3. **Interpretasi Tren Keuangan**: AI membantu menjelaskan makna tren berdasarkan visualisasi yang dihasilkan.
4. **Potensi Risiko Keuangan**: Identifikasi potensi risiko berdasarkan pola data.

Cara kerja fitur:
- Data diproses dengan Pandas, divisualisasikan menggunakan Matplotlib/Seaborn.
- AI digunakan untuk menjelaskan hasil analisis dan memberikan insight tambahan secara otomatis.

## AI Support Explanation
Dalam proyek ini, **AI generatif (IBM Granite AI)** digunakan untuk dua hal utama:
1. **Code Generation**  
   AI menerima prompt dari pengguna, kemudian menghasilkan kode Python secara otomatis. Misalnya, jika pengguna ingin membuat grafik tren pendapatan, cukup memberikan prompt:  
   *"Buat grafik tren pendapatan berdasarkan kolom Revenue per bulan"*  
   AI akan menuliskan kode lengkap untuk visualisasi.

2. **Prompt Engineering**  
   Pengguna dapat membuat prompt khusus untuk menyesuaikan kebutuhan analisis. Semakin jelas prompt yang diberikan, semakin relevan kode yang dihasilkan. Hal ini memungkinkan proses analisis data menjadi lebih fleksibel, cepat, dan adaptif.

Dampak nyata penggunaan AI dalam proyek ini adalah:
- **Efisiensi waktu**: Mengurangi waktu penulisan kode manual.
- **Minim kesalahan sintaks**: Kode yang dihasilkan sudah siap dijalankan.
- **Aksesibilitas**: Pengguna tanpa pengalaman coding dapat tetap melakukan analisis dengan memberikan prompt sederhana.

---

## Cara Menjalankan Proyek
1. Clone repository ini.
2. Install dependencies dengan perintah:
   ```bash
   pip install -r requirements.txt
   ```
3. Jalankan aplikasi Streamlit:
   ```bash
   streamlit run dashboard.py
   ```
4. Upload dataset keuangan Anda, lalu gunakan fitur dashboard untuk eksplorasi insight.

---

## Author
Dikembangkan oleh **Heinz Metrosan Donradt Siahaan**  
Bagian dari program *AI-Powered Financial Insight Dashboard*.
