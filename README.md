# Blog Pribadi Farhan

Ini adalah proyek blog pribadi sederhana yang dibangun sebagai latihan untuk mengasah skill saya di bagian CRUD menggunakan bahasa JavaScript.

Blog ini memiliki fungsionalitas **CRUD (Create, Read, Update, Delete)** penuh dan menampilkan desain **Neumorphism (Soft UI)** yang modern.


<img width="1916" height="907" alt="Screenshot 2025-11-11 213240" src="https://github.com/user-attachments/assets/314f8d6e-9dcb-4453-a57c-2100ea0adadb" />


## 🚀 Fitur Utama

* **Buat Postingan:** Menulis dan mempublikasikan postingan baru melalui form.
* **Lihat Postingan:** Semua postingan ditampilkan secara kronologis di halaman utama.
* **Edit Postingan:** Memperbarui judul dan isi postingan yang sudah ada.
* **Hapus Postingan:** Menghapus postingan dari daftar.
* **Desain Neumorphism:** Tampilan "Soft UI" yang unik di mana elemen terlihat "timbul" dari latar belakang.
* **Animasi:** Efek *hover* dan *focus* yang memuaskan, serta animasi *fade-in* saat memuat postingan.

---

## 🛠️ Teknologi yang Digunakan

* **Backend:**
    * [**Node.js**](https://nodejs.org/): Lingkungan eksekusi JavaScript sisi server.
    * [**Express.js**](https://expressjs.com/): Framework untuk membangun aplikasi web dan menangani routing.
* **Frontend:**
    * [**EJS (Embedded JavaScript)**](https://ejs.co/): Templating engine untuk merender HTML secara dinamis.
    * **CSS3:** Untuk styling kustom, terutama untuk menciptakan efek Neumorphism dengan `box-shadow`.
* **Struktur Proyek:**
    * Menggunakan *partials* EJS untuk komponen yang dapat digunakan kembali (seperti header dan footer).

---

## ⚙️ Instalasi dan Menjalankan Proyek

Untuk menjalankan proyek ini di komputer Anda:

1.  **Clone repository ini:**
    ```bash
    git clone https://github.com/farhandavin/blog_pribadi_farhan.git
    ```

2.  **Masuk ke direktori proyek:**
    ```bash
    cd blog_pribadi_farhan
    ```

3.  **Install dependencies:**
    ```bash
    npm install
    ```
    *(Pastikan Anda sudah meng-install `express`, `ejs`, dan `body-parser`)*

4.  **Jalankan server:**
    ```bash
    node index.js
    ```
    *(Atau `nodemon index.js` jika Anda menggunakannya)*

5.  **Buka di browser:**
    Buka `http://localhost:3000` di browser Anda.
