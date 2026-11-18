# Katalog Produk

Aplikasi desktop berbasis JavaFX dan SQLite untuk mengelola data katalog produk (tambah, lihat, ubah, dan hapus data).

## Spesifikasi & Library

- Java 17
- JavaFX 21 (Controls & FXML)
- SQLite JDBC 3.49.1.0
- Apache Maven

Database lokal (`katalog.db`) dan tabel `produk` otomatis dibuat di dalam folder `data/` saat aplikasi pertama kali dijalankan.


## Cara Menjalankan Aplikasi

Melalui terminal atau Command Prompt di folder proyek:

```bash
mvn clean javafx:run
```

Jika menggunakan Apache NetBeans:
1. Buka proyek di NetBeans.
2. Buka menu **Properties > Actions > Run project**, lalu ubah bagian **Execute Goals** menjadi `javafx:run`.
3. Tekan **F6** untuk menjalankan aplikasi.

## screenshoot tampilan aplikasi
<img width="1227" height="970" alt="Screenshot 2026-11-18 181229" src="https://github.com/user-attachments/assets/55b0b4db-a493-4610-a0f0-4b99e1645dc6" />
<img width="1245" height="977" alt="Screenshot 2026-11-18 181135" src="https://github.com/user-attachments/assets/f1d8071f-434e-4caf-9d75-fdfdfb29a396" />
