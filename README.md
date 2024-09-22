# Analisis-Time-Series-Peramalan-Harga-Saham-Bank-
Repository ini berisi notebook Jupyter berjudul Analisis_Data_Time_Series_(Saham_Bank).ipynb, yang melakukan analisis data time series untuk memprediksi pergerakan harga saham di sektor perbankan. Analisis ini menggunakan teknik statistik dan model time series untuk memahami pola historis serta memproyeksikan tren harga saham di masa depan.

# Data yang Digunakan
Dataset yang digunakan dalam analisis ini berisi data historis harga saham dari sektor perbankan, dan mencakup beberapa variabel utama sebagai berikut:
- Tanggal: Tanggal observasi saham pada skala harian, yang digunakan sebagai indeks time series.
- Harga Penutupan Saham: Harga saham pada saat penutupan perdagangan harian, digunakan sebagai variabel target (dependent) untuk pemodelan prediktif.
- Volume Perdagangan: Jumlah saham yang diperdagangkan per hari, digunakan untuk membantu memahami dinamika perdagangan dan mendukung analisis tren.
- Harga Tertinggi dan Terendah: Harga tertinggi dan terendah saham dalam sehari, memberikan informasi tambahan mengenai volatilitas harian.
- Harga Pembukaan: Harga saham pada awal perdagangan harian, yang dapat digunakan untuk analisis komparatif dengan harga penutupan.
- Data ini bersifat time series dengan observasi yang diambil dalam interval waktu harian. Analisis ini akan berfokus pada bagaimana harga saham berubah seiring waktu dan faktor-faktor apa yang memengaruhi pergerakan harga tersebut.

# Analisis dan Metodologi
Analisis ini dilakukan melalui beberapa langkah, antara lain:
- Eksplorasi Data: Melakukan pembersihan data, visualisasi tren harga saham, dan deskripsi statistik untuk mendapatkan wawasan awal mengenai pola data.
- Pemodelan Time Series: Membangun model time series menggunakan metode seperti ARIMA (AutoRegressive Integrated Moving Average), untuk menangkap pola jangka pendek dan jangka panjang dalam harga saham.
- Validasi dan Evaluasi Model: Mengevaluasi performa model prediksi dengan menggunakan metrik seperti Mean Squared Error (MSE) dan Mean Absolute Percentage Error (MAPE), serta membandingkan performa model berdasarkan data out-of-sample.
- Proyeksi Harga Saham: Menggunakan model terpilih untuk memprediksi harga saham dalam jangka waktu tertentu ke depan, memberikan wawasan mengenai tren pergerakan saham di masa mendatang.

# Hasil dan Kesimpulan
Dari notebook ini, akan didapatkan:
- Visualisasi tren historis harga saham dan volume perdagangan.
- Model prediktif time series yang dapat digunakan untuk memproyeksikan harga saham di masa mendatang.
- Evaluasi model menggunakan metrik seperti MSE dan MAPE untuk mengukur performa prediksi berdasarkan data historis.
  
Proyeksi ini dapat bermanfaat untuk keputusan terkait investasi di sektor perbankan, dengan mempertimbangkan tren harga saham historis dan faktor volatilitas.
