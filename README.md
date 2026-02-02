# Log_in_Portal_ortu
Log in portal orang tua
# Al-Kautsar Connect (Portal Wali Murid)

Aplikasi Web Mobile-First untuk memantau perkembangan siswa SMP IT Al-Kautsar. Portal ini dirancang khusus untuk orang tua/wali murid dengan fokus pada aspek Akademik, Karakter (Akhlak), dan Al-Qur'an (T2Q).

![Status](https://img.shields.io/badge/Status-Prototype-green)
![Tech](https://img.shields.io/badge/Stack-HTML%20%7C%20Tailwind%20%7C%20JS-blue)

## 📱 Fitur Utama
1.  **Dashboard Ringkas**: Menampilkan persentase kehadiran dan status harian siswa secara real-time.
2.  **Laporan T2Q**: Monitoring hafalan dan tahsin siswa.
3.  **Bina Pribadi**: Laporan perkembangan akhlak dan ibadah harian.
4.  **Catatan Wali Kelas**: Komunikasi satu arah dari guru ke orang tua.
5.  **Tanpa Fitur Keuangan**: Fokus murni pada pendidikan dan pembinaan.

## 🛠️ Cara Menggunakan (Untuk Developer)
Repository ini adalah **Frontend Prototype**. Belum terhubung ke Database MySQL/API.

1.  Clone repository ini atau download ZIP.
2.  Buka file `index.html` di browser (Chrome/Edge/Safari).
3.  **Login Demo**:
    * Username: (Bebas, misal: 12345)
    * Password: (Bebas)
4.  Klik "Masuk Portal" untuk melihat Dashboard.

## 📂 Struktur File
* `index.html`: Struktur utama aplikasi dan styling menggunakan Tailwind CSS (CDN).
* `script.js`: Logika aplikasi, simulasi login, dan dummy data (Mock Data).

## 🎨 Kustomisasi Data
Untuk mengubah nama siswa atau data dummy, buka file `script.js` dan edit objek `dataSiswa`:

```javascript
const dataSiswa = {
    nama: "Ganti Nama Disini",
    nis: "123456",
    ...
};
