📒 Notes App – Flutter

Aplikasi Notes App adalah aplikasi pencatatan sederhana yang dibangun menggunakan Flutter, Bloc/Cubit, dan local storage (Hive).
Aplikasi ini memungkinkan pengguna membuat, mengedit, dan menghapus catatan secara offline dengan cepat dan mudah.

📱 Fitur Aplikasi
✅ 1. Tambah Catatan

Pengguna dapat menambahkan catatan baru dengan judul dan isi.

✅ 2. Edit Catatan

Catatan yang sudah ada dapat diedit kapan saja.

✅ 3. Hapus Catatan

Catatan dapat dihapus secara permanen.

✅ 4. Simpan Data Secara Offline

Menggunakan Hive, seluruh catatan tersimpan di perangkat tanpa koneksi internet.

✅ 5. State Management BLoC / Cubit

Menggunakan pattern Bloc agar data lebih stabil, terstruktur, dan mudah dikelola.

✅ 6. UI Clean dan Responsive

Tampilan dibuat sederhana dan nyaman digunakan.

🛠️ Teknologi yang Digunakan
Teknologi	Keterangan
Flutter	Framework utama
Dart	Bahasa pemrograman
Hive	Local NoSQL database
flutter_bloc	State management
VS Code / Android Studio	Text editor
🚀 Cara Instalasi

Ikuti langkah berikut jika ingin menjalankan project ini:

1️⃣ Clone Repository
git clone https://github.com/username/notes_app.git
cd notes_app

2️⃣ Install Dependencies
flutter pub get

3️⃣ Generate Hive Adapter (jika menggunakan build_runner)

Jika kamu menggunakan TypeAdapter:

flutter packages pub run build_runner build

4️⃣ Jalankan Aplikasi
flutter run
