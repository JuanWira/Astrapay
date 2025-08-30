# Astrapay

Cara Menjalankan Backend (Spring Boot)
1. Masuk ke folder project backend.
2. Jalankan perintah: mvn spring-boot:run -Dspring-boot.run.main-class=com.astrapay.NotesApplication
3. Aplikasi jalan di: http://localhost:8000

Endpoint API
1. GET /api/v1/notes → Ambil semua notes
2. GET /api/v1/notes/{id} → Ambil detail note by id
3. POST /api/v1/notes → Tambah note baru
4. { "title": "Judul", "content": "Isi note" }
5. DELETE /api/v1/notes/{id} → Hapus note by id

Cara Menjalankan Frontend (Angular)
1. Masuk ke folder Angular (notes-ui).
2. Install dependency:
3. npm install
4. Jalankan aplikasi: ng serve --open
5. UI dapat diakses di: http://localhost:4200
