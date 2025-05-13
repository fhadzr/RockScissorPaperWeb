## 🪨📄✂️ RockScissorPaperWeb

**RockScissorPaperWeb** adalah sebuah aplikasi web berbasis JavaScript yang dapat mendeteksi gesture tangan *Rock*, *Paper*, atau *Scissors* menggunakan kamera dan model machine learning buatan sendiri.

### 🚀 Fitur

* Live capture dari webcam.
* Kumpulan data pelatihan langsung melalui tombol Rock, Paper, Scissors.
* Pelatihan model secara langsung di browser menggunakan TensorFlow\.js.
* Prediksi gesture secara real-time.
* Opsi untuk menyimpan model hasil pelatihan ke perangkat lokal.

---

### ⚙️ Teknologi yang Digunakan

* [TensorFlow.js](https://www.tensorflow.org/js) – untuk membuat dan melatih model ML di browser.
* HTML5 + JavaScript – untuk antarmuka dan interaksi pengguna.
* Webcam API – untuk mengakses kamera pengguna.

---

### 📦 Struktur File

```plaintext
index.html           # File utama HTML
webcam.js            # Mengatur akses kamera
rps-dataset.js       # Menyimpan data latih
webmodel.js          # Arsitektur dan pelatihan model ML
```

---

### 📋 Cara Menggunakan

1. Clone repo:

   ```bash
   git clone https://github.com/username/RockScissorPaperWeb.git
   cd RockScissorPaperWeb
   ```

2. Buka file `index.html` langsung di browser (cukup klik dua kali, atau via VSCode Live Server).

3. Izinkan akses kamera.

4. Klik tombol **Rock**, **Paper**, atau **Scissors** untuk mengumpulkan contoh gesture.

5. Setelah cukup data, klik **Train Network** untuk melatih model.

6. Klik **Start Predicting** untuk mulai prediksi gesture secara real-time.

7. Klik **Download Model** (jika kamu menambahkan tombol tersebut) untuk menyimpan model ke disk.

---

### 📂 Contoh Kode (HTML)

```html
<video autoplay playsinline muted id="wc" width="224" height="224"></video>
<button type="button" id="0" onclick="handleButton(this)">Rock</button>
<button type="button" id="1" onclick="handleButton(this)">Paper</button>
<button type="button" id="2" onclick="handleButton(this)">Scissors</button>
...
```

---

### 📈 Catatan Pengembangan

* Model saat ini bersifat sederhana dan dilatih langsung di client.
* Cocok untuk pembelajaran tentang machine learning di browser.

---

### 🧠 Referensi

* [TensorFlow.js Documentation](https://www.tensorflow.org/js)
* [Rock Paper Scissors TFJS Example](https://github.com/tensorflow/tfjs-examples)

---

### 📄 Lisensi

MIT License
