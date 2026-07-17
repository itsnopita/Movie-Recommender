# 🎬 Movie Recommender System

Aplikasi **Movie Recommender System** merupakan sistem rekomendasi film berbasis web yang dibangun menggunakan **Python** dengan framework **Django**. Sistem ini memungkinkan pengguna menemukan rekomendasi film berdasarkan data rating, tag, dan preferensi pengguna. Sistem memanfaatkan dataset film yang berisi informasi movie, rating, dan tag sebagai dasar proses rekomendasi. Selain itu, aplikasi terintegrasi dengan **TMDB API** untuk menampilkan poster film sehingga tampilan menjadi lebih menarik.

Project ini dibuat sebagai salah satu tugas **Ujian Akhir Semester (UAS)**.

---

## ✨ Fitur Utama

- 🔐 Login & Logout
- 👤 Registrasi Pengguna
- 🎬 Menampilkan daftar film
- ⭐ Memberikan rating film
- 🏷️ Menambahkan tag film
- ❤️ Menyimpan film favorit
- 🤖 Sistem rekomendasi film
- 🖼️ Menampilkan poster film dari TMDB API
- 📊 Dashboard Admin
- 👥 Manajemen User
- 🎞️ Manajemen Movie
- ⭐ Manajemen Rating
- 🏷️ Manajemen Tag
- 📈 Statistik Dashboard

---

## 🛠️ Teknologi yang Digunakan

| Teknologi | Keterangan |
|------------|------------|
| Python | Bahasa Pemrograman |
| Django | Framework Web |
| HTML5 | Struktur Halaman |
| CSS3 | Tampilan Website |
| JavaScript | Interaksi Website |
| Bootstrap | User Interface |
| MySQL | Database Management System |
| TMDB API | Poster Film |

---

## 🗄️ Database

Database Management System (DBMS) yang digunakan pada aplikasi ini adalah:

- **MySQL**

Dataset yang digunakan meliputi:

- Movies Dataset
- Ratings Dataset
- Tags Dataset
- Links Dataset

---

## 📂 Struktur Project

```
movie_recommender/
│
├── accounts/
├── dataset/
├── favorites/
├── media/
├── movie_recommender/
├── movies/
├── ratings/
├── recommendations/
├── static/
├── tags/
├── templates/
├── manage.py
├── requirements.txt
└── README.md
```

---

## ⚙️ Cara Menjalankan Project

### 1. Clone Repository

```bash
git clone https://github.com/itsnopita/Movie-Recommender.git
```

### 2. Masuk ke Folder Project

```bash
cd Movie-Recommender
```

### 3. Membuat Virtual Environment

```bash
python -m venv venv
```

### 4. Aktifkan Virtual Environment

Windows

```bash
venv\Scripts\activate
```

Linux / MacOS

```bash
source venv/bin/activate
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

### 6. Konfigurasi Database MySQL

Buat database baru, kemudian sesuaikan konfigurasi pada file:
movie_recommender/settings.py

```
```
### 7. Jalankan Migrasi

```bash
python manage.py migrate
```
### 8. Jalankan Server

```bash
python manage.py runserver
Buka browser:
http://127.0.0.1:8000/
```
## 🎥 Demo Video

Video demonstrasi aplikasi dapat dilihat melalui YouTube:

**Nokiday - Movie Recommender**

https://youtu.be/IlbID3V2SHM?si=VasMzpnE9KicEAK8

---

## 👩‍💻 Developer

**Nofita Ayu Sabila**

Universitas Banten Jaya

---

## 📄 Lisensi

Project ini dibuat untuk keperluan pembelajaran dan tugas akademik.
