1. Membersihkan pohon kerja dengan menghapus file yang tidak berada di bawah kendali versi secara rekursif, mulai dari direktori saat ini.
2. -d
Biasanya, ketika tidak ada <path> yang ditentukan, git clean tidak akan muncul kembali ke direktori yang tidak terlacak untuk menghindari penghapusan terlalu banyak. Tentukan -d untuk membuatnya berulang ke direktori seperti itu juga. Jika ada jalur yang ditentukan, -d tidak relevan; semua file yang tidak terlacak yang cocok dengan jalur yang ditentukan (dengan pengecualian untuk direktori git bersarang yang disebutkan di bawah --force) akan dihapus.
-F
--memaksa
Jika variabel konfigurasi Git clean.requireForce tidak disetel ke false, git clean akan menolak untuk menghapus file atau direktori kecuali diberikan -for -i. Git akan menolak untuk memodifikasi repositori git bersarang yang tidak terlacak (direktori dengan subdirektori .git) kecuali -f kedua diberikan.
3. git branch <nama cabang>
4. Perbedaan antara penggabungan ini dan penggabungan maju cepat adalah bahwa penggabungan dilakukan dengan strategi rekursif
5. git checkout <nama cabang>
6. git reset
7. Menghapus cabang REMOTELY. Berikut perintah untuk menghapus cabang dari jarak jauh: git push <remote> --delete <branch>.
8. Perintah Diff digunakan di git untuk melacak perbedaan antara perubahan yang dibuat pada file.
9. git rm <file> --cached.
10. Konflik penggabungan dapat terjadi saat menggabungkan cabang, rebasing cabang, atau memilih komit.
