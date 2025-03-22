# 🎓 Proyek Prediksi Dropout Siswa

Proyek ini merupakan proyek data science yang bertujuan membantu **Jaya Jaya Institut** dalam mengidentifikasi siswa yang berisiko mengalami dropout. Model klasifikasi digunakan untuk melakukan prediksi, dan prototipe sistem disediakan dalam bentuk aplikasi web berbasis Streamlit.

---

## 🚀 Capaian Proyek

✅ Aplikasi prediksi dropout berbasis Streamlit  
✅ Dashboard visualisasi menggunakan Metabase  
✅ Model machine learning dan fitur yang telah dilatih  
✅ Visualisasi faktor-faktor penting yang memengaruhi dropout

---

## 🧪 Model Machine Learning

- Algoritma: RandomForestClassifier
- Akurasi: ±82%
- Fitur yang digunakan: performa akademik, demografi, status pembayaran, dll.
- Proses training dan evaluasi dilakukan di Google Colab menggunakan Scikit-learn.

---

## 🔗 Aplikasi Streamlit

Coba aplikasi prediksi dropout secara online:  
➡️ [https://7fn9zar3462qxe3rilt4ve.streamlit.app/](https://7fn9zar3462qxe3rilt4ve.streamlit.app/)

Tidak memerlukan login. Masukkan data siswa, klik tombol "Prediksi Dropout", dan lihat hasil prediksi.

---

## 📊 Dashboard (Metabase)

Dashboard dibuat menggunakan **Metabase (melalui Docker)** dan menyajikan insight visual terkait performa siswa dan tren dropout.

Isi visualisasi:

- Distribusi siswa dropout
- Dropout berdasarkan jenis kelamin
- Dropout berdasarkan status beasiswa
- Dropout berdasarkan status pembayaran
- Rata-rata nilai semester 1 berdasarkan status dropout
- Rata-rata jumlah evaluasi berdasarkan status dropout

📁 File: `metabase.db.mv.db`  
🖼️ Screenshot: `gevinfaza1702-dashboard.png`  
📧 Email login: `gevinfaza95@gmail.com.com`  
🔐 Password: `Ninjasaga123+`

Menjalankan Metabase secara lokal:

```bash
docker run -d -p 3000:3000 --name metabase metabase/metabase
```
