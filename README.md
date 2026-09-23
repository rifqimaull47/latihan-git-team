# Latihan Git Team

Repository ini dibuat untuk latihan kolaborasi Git menggunakan branch,
Pull Request, merge conflict, dan penanganan kebocoran file `.env`.

## Branch

- `main`
- `feature/greeting`
- `feature/footer`

## Fitur

- Greeting message
- Footer message

## Simulasi Conflict

Siswa A mengubah bagian greeting pada `index.js`.
Siswa B mengubah bagian yang sama untuk menambahkan footer.

Siswa A melakukan merge terlebih dahulu sehingga terjadi conflict
ketika Siswa B melakukan merge.

Conflict diselesaikan dengan mempertahankan kedua perubahan.

## Simulasi Kebocoran

File `.env` sengaja dibuat dan di-commit menggunakan secret palsu.

Penanganan:

1. Secret palsu dianggap telah dicabut.
2. `.env` ditambahkan ke `.gitignore`.
3. `.env` dihapus dari repository.
4. History repository dibersihkan.
5. `.env.example` dibuat sebagai template konfigurasi.

## Anggota

- Siswa A: Nama
- Siswa B: Nama