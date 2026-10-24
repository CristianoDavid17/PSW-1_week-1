1. Repository aman
repository aman dan ada dalam satu branch. Juga ada perubahan yang tercatat pada branch fitur.
2. Simulasi Review
Pada kegiatan simulasi review, dilakukan pemeriksaan perubahan pada branch fitur menggunakan perintah git diff untuk membandingkan hasil kerja dengan branch utama. Hasil review memperoleh dua masukan, yaitu perlunya memperbaiki tampilan judul agar lebih jelas dan menambahkan penjelasan cara mengakses fitur pada README. Berdasarkan masukan tersebut, dilakukan revisi pada file yang terkait, kemudian perubahan disimpan ke repositori melalui commit sebagai tindak lanjut dari proses review. Kegiatan ini menunjukkan bahwa review membantu menemukan kekurangan dan meningkatkan kualitas hasil pekerjaan sebelum digabungkan ke branch utama.
3. Menggabungkan Perubahan
Pada tahap ini dilakukan perpindahan ke branch utama dan penggabungan branch fitur menggunakan perintah git merge. Proses merge berhasil dilakukan tanpa ditemukan konflik sehingga seluruh perubahan pada fitur dapat diterapkan ke branch utama. Hasil penggabungan kemudian diperiksa melalui git log --oneline --max-count=5 untuk memastikan commit hasil merge tercatat pada riwayat repository. Bukti keberhasilan dapat dilihat dari munculnya commit terbaru pada log Git yang menunjukkan bahwa branch fitur telah berhasil digabungkan ke branch utama.

Checklist:
- Semantik ==> 