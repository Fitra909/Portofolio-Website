# 🚀 Panduan Git & GitHub Push Project dari Awal

Panduan ini membantu kamu untuk upload project dari lokal ke GitHub menggunakan Git.  
Cocok untuk pemula atau buat catatan pribadi kamu.

---

## 🧾 1. Setup Git (sekali saja di komputer)

```bash
git config --global user.name "Nama Kamu"
git config --global user.email "emailkamu@example.com"

Cek apakah Git sudah terinstall:
git --version

🗂 2. Inisialisasi Git di Folder Project
Masuk ke folder project kamu, lalu ketik:
git init

📥 3. Tambahkan Semua File
git add .
Atau tambahkan file tertentu saja:
git add index.html style.css

💬 4. Commit Perubahan
git commit -m "Initial commit: tambah file utama"

🌐 5. Buat Repository Baru di GitHub
Buka https://github.com
Klik tombol New Repository
Isi nama repository (misal: portfolio-website)
Jangan centang "Initialize with README"
Klik Create repository

🔗 6. Hubungkan ke Repository GitHub
Ganti usernamekamu dan nama-repo dengan punya kamu.

🚀 7. Push Project ke GitHub
git branch -M main
git push -u origin main

Jika diminta login:
Username: akun GitHub kamu
Password: gunakan Personal Access Token (PAT)

🔁 8. Push Perubahan Selanjutnya
git add .
git commit -m "Update file/folder"
git push

🔍 9. Cek Status (opsional)
git status

🌱 10. Aktifkan GitHub Pages
1.Buka repo kamu di GitHub
2.Klik Settings > Pages
3.Di bagian Build and deployment:
  - Source: Deploy from a branch
  - Branch: main
  - Folder: / (root)
4.Klik Save
5.Tunggu beberapa detik sampai muncul link:

✅ Tips Tambahan
Warna hijau di GitHub = kamu aktif push
Push rutin bikin portofolio kamu aktif
README.md bisa jadi dokumentasi project kamu
Preview website lokal bisa pakai Live Server di VS Code

Selamat ngoding! 💻🔥
Jangan lupa commit, push, dan grow up skill kamu tiap hari 🌱


