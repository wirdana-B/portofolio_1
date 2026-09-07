# Analisis Penjualan 2025

Repositori ini berisi analisis data penjualan untuk tahun 2025 (`penjualan_2025.csv`) menggunakan Python.

## File

*   `python_for_data_science_numpy_pandas_matplotlib.ipynb`: Jupyter Notebook yang memuat seluruh proses analisis data, mulai dari pemuatan data, eksplorasi, analisis, hingga visualisasi.

## Library yang Digunakan

Proses analisis dalam notebook ini memanfaatkan library populer dalam ekosistem Data Science Python:
*   **NumPy**: Digunakan untuk komputasi numerik, perhitungan statistik dasar (total, rata-rata, median, standar deviasi) dari pendapatan.
*   **Pandas**: Digunakan untuk manipulasi dan analisis data tabular. Meliputi proses memuat data dari file CSV, mengeksplorasi data, dan melakukan agregasi/pengelompokan data berdasarkan kategori produk, region, dan tren bulanan.
*   **Matplotlib**: Digunakan untuk memvisualisasikan data agar pola dan wawasan (insights) dapat lebih mudah dipahami.

## Rangkuman Analisis

Notebook ini mengeksplorasi data untuk menjawab beberapa pertanyaan kunci, antara lain:
*   Berapa total dan rata-rata pendapatan bersih dari seluruh penjualan?
*   Bagaimana distribusi pendapatan bersih jika dikelompokkan berdasarkan **Kategori** produk?
*   Bagaimana distribusi pendapatan bersih jika dikelompokkan berdasarkan **Region**?
*   Bagaimana tren pendapatan bulanan selama tahun 2025?

## Cara Menjalankan

1.  Pastikan Anda telah menginstal Python dan Jupyter Notebook.
2.  Instal library yang diperlukan jika belum ada:
    ```bash
    pip install numpy pandas matplotlib
    ```
3.  Pastikan file data `penjualan_2025.csv` berada di direktori yang sama dengan file notebook.
4.  Buka dan jalankan `python_for_data_science_numpy_pandas_matplotlib.ipynb` menggunakan Jupyter.
