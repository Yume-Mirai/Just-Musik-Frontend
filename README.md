# Just-Musik 🎵

Aplikasi web manajemen musik modern yang dibangun dengan React dan Vite. Just-Musik memungkinkan pengguna untuk mengelola koleksi musik, mengunggah lagu, membuat playlist favorit, dan menikmati pengalaman streaming musik yang responsif.

## ✨ Fitur Utama

- **🔐 Autentikasi Pengguna**: Sistem login dan registrasi yang aman dengan JWT
- **🎵 Manajemen Musik**: Unggah, edit, dan kelola koleksi musik Anda
- **❤️ Sistem Favorit**: Tandai lagu favorit untuk akses mudah
- **📚 Perpustakaan Musik**: Jelajahi dan kelola seluruh koleksi musik
- **👤 Profil Pengguna**: Kelola informasi profil dan preferensi
- **🎶 Player Musik**: Putar musik dengan kontrol pemutaran lengkap
- **📱 Responsive Design**: Antarmuka yang optimal di semua perangkat

## 🚀 Teknologi yang Digunakan

### Frontend
- **React 19.1.1** - Library JavaScript untuk membangun antarmuka pengguna
- **Vite 7.1.2** - Build tool yang cepat dan modern
- **React Router DOM 7.8.2** - Routing untuk aplikasi single-page
- **Axios 1.11.0** - HTTP client untuk komunikasi dengan API

### Development Tools
- **ESLint 9.33.0** - Linting untuk menjaga kualitas kode
- **Vite React Plugin** - Plugin khusus untuk pengembangan React

## 📋 Prasyarat

Sebelum menjalankan aplikasi ini, pastikan Anda telah menginstal:

- **Node.js** (versi 16 atau lebih tinggi)
- **npm** atau **pnpm** sebagai package manager

## 🛠️ Instalasi

1. **Clone repository**
   ```bash
   git clone <repository-url>
   cd just-musik-frontend
   ```

2. **Install dependencies**
   ```bash
   npm install
   # atau jika menggunakan pnpm
   pnpm install
   ```

3. **Jalankan development server**
   ```bash
   npm run dev
   # atau
   pnpm dev
   ```

4. **Buka browser dan akses**
   ```
   http://localhost:5173
   ```

## 📜 Scripts yang Tersedia

- `npm run dev` - Menjalankan development server
- `npm run build` - Build aplikasi untuk production
- `npm run preview` - Preview production build secara lokal
- `npm run lint` - Menjalankan ESLint untuk memeriksa kode

## 🏗️ Struktur Proyek

```
src/
├── components/          # Komponen React yang dapat digunakan kembali
│   ├── auth/           # Komponen autentikasi (Login, Register)
│   ├── common/         # Komponen umum (LoadingSpinner, Pagination, dll)
│   ├── layout/         # Komponen layout (Navbar, Sidebar, Footer)
│   └── songs/          # Komponen terkait musik (Player, SongForm, dll)
├── context/            # React Context untuk state management
├── hooks/              # Custom React hooks
├── pages/              # Halaman-halaman aplikasi
├── services/           # Layanan API dan konfigurasi
├── styles/             # File CSS untuk styling
└── utils/              # Utility functions
```

## 🔧 Konfigurasi

### API Configuration
API endpoint dikonfigurasi di `src/services/api.js`:
```javascript
const API_BASE_URL = 'https://asfariganteng.up.railway.app/api'
```

### Environment Variables
Buat file `.env` jika diperlukan untuk konfigurasi environment-specific:
```env
VITE_API_URL=https://your-api-url.com/api
```

## 🔐 Autentikasi

Aplikasi menggunakan sistem autentikasi berbasis JWT:

1. **Registrasi**: Pengguna dapat membuat akun baru
2. **Login**: Autentikasi dengan email dan password
3. **Protected Routes**: Halaman tertentu memerlukan autentikasi
4. **Auto Logout**: Token expired akan mengarahkan ke halaman login

## 🎵 Fitur Musik

### Manajemen Lagu
- Unggah lagu dalam berbagai format
- Edit metadata lagu (judul, artis, album)
- Hapus lagu dari koleksi
- Cari dan filter lagu

### Playlist & Favorit
- Tambahkan lagu ke favorit
- Kelola playlist pribadi
- Akses cepat ke lagu favorit

## 🌟 Fitur Unggulan

- **Responsive Design**: Bekerja optimal di desktop dan mobile
- **Modern UI/UX**: Antarmuka yang bersih dan intuitif
- **Fast Loading**: Optimasi performa dengan Vite
- **Real-time Updates**: Sinkronisasi data real-time
- **Error Handling**: Penanganan error yang komprehensif

## 🤝 Kontribusi

Kontribusi selalu diterima! Berikut cara berkontribusi:

1. Fork repository
2. Buat branch untuk fitur baru (`git checkout -b feature/AmazingFeature`)
3. Commit perubahan (`git commit -m 'Add some AmazingFeature'`)
4. Push ke branch (`git push origin feature/AmazingFeature`)
5. Buat Pull Request

## 📝 Lisensi

Proyek ini dilisensikan di bawah lisensi MIT - lihat file [LICENSE](LICENSE) untuk detail lebih lanjut.

## 📞 Kontak

Jika Anda memiliki pertanyaan atau masukan, silakan hubungi tim pengembang.

---

**Just-Musik** - Kelola musik Anda dengan mudah dan nikmati pengalaman streaming yang luar biasa! 🎵✨