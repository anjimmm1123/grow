# Growtopia Login Backend

Backend untuk sistem login Growtopia dengan fitur Fluid Compute dan Skew Protection.

## Persyaratan

- Node.js (v14 atau lebih tinggi)
- npm (v6 atau lebih tinggi)

## Instalasi

1. Clone repository ini
```bash
git clone https://github.com/username/growtopia-login-backend.git
cd growtopia-login-backend
```

2. Install dependencies
```bash
npm install
```

## Penggunaan

### Development Mode
```bash
npm run dev
```
Aplikasi akan berjalan di `http://localhost:5000` dengan hot-reload aktif.

### Production Mode
```bash
npm start
```
Aplikasi akan berjalan di `http://localhost:5000`

### Build
```bash
npm run build
```

## Fitur

- Login system dengan validasi
- Registrasi user baru
- Fluid Compute untuk optimasi performa
- Skew Protection untuk keamanan
- Rate limiting untuk mencegah abuse
- Kompresi response untuk performa lebih baik

## Struktur Proyek

```
growtopia-login-backend/
├── index.js              # Entry point aplikasi
├── public/              # Publish Directory - File statis
│   ├── css/            # File CSS
│   ├── js/             # File JavaScript
│   └── html/           # Template EJS
│       ├── dashboard.ejs
│       └── register.ejs
├── package.json        # Konfigurasi proyek
└── README.md          # Dokumentasi
```

## Publish Directory

Direktori `public/` adalah Publish Directory yang berisi semua file yang dapat diakses publik:

- `public/css/`: Berisi file CSS untuk styling
- `public/js/`: Berisi file JavaScript untuk client-side
- `public/html/`: Berisi template EJS untuk halaman web

Semua file dalam direktori ini dapat diakses melalui URL:
- CSS: `http://localhost:5000/css/`
- JS: `http://localhost:5000/js/`
- HTML: `http://localhost:5000/html/`

## Lisensi

MIT

## Hosting Usage

Tutorial:

[![Tutorial Videos](http://img.youtube.com/vi/8OXt1tHmeAM/0.jpg)](http://www.youtube.com/watch?v=8OXt1tHmeAM)

## Path Information

- `/` - The main page
- `/player/login/dashboard` - The dashboard for the login modals
- `/player/growid/login/validate` - The validation for the GrowID login
  
## Contact

You can contact me at teleram my username is [@yoruakio](https://t.me/yoruakio) or join my discord server [Nakai Community](https://discord.com/invite/ESsBxptJqr).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
