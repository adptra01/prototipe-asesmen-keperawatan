# Prototipe Format Asesmen & Observasi Keperawatan Rawat Inap

Prototype statis (satu file HTML, tanpa dependency) untuk usulan penggabungan seluruh
form asesmen/pengkajian rawat inap menjadi **satu format lengkap dari awal sampai akhir**.

Dibuat dari hasil observasi read-only terhadap MORBIS RSUD H. Abdul Manap pada 26–27 November 2026.
Data yang tampil adalah data contoh, bukan data pasien asli.

Fitur:
- 8 bagian format (Identitas, Asesmen Awal, Skrining, Observasi, Diagnosis, Rencana, Evaluasi, Linimasa)
- Field asesmen berubah sesuai jenis pasien (RI, ICU, Anak, Obgyn, Syaraf, Neonatus, IGD/Pra-bedah)
- Field observasi berubah sesuai jenis (EWS, MEOWS, PWS, Jatuh, Nyeri)
- Entri baru bersifat append-only dan muncul di linimasa
- Cetak / Simpan PDF, status tersimpan di URL, akses keyboard

Didesain untuk dibahas bersama tim sebelum implementasi di MORBIS.
