MONITORING GORONG-GORONG

Versi siap untuk Vercel/GitHub.
- NRP otomatis berdasarkan NAMA INSPEKTOR.
- Field NRP dibuat read-only.
- NRP ditampilkan pada Monitoring dan Riwayat.
- Database menggunakan Supabase yang sudah dikonfigurasi pada aplikasi.

Catatan: kolom `nrp` harus tersedia pada tabel public.inspections di Supabase agar NRP tersimpan ke database.
Jika belum ada, jalankan: alter table public.inspections add column if not exists nrp text;
