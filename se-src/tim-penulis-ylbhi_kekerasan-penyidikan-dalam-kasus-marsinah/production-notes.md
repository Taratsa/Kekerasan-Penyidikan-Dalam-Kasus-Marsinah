# Catatan produksi

- Sumber dan keterangan edisi: lihat `se-imprint.md` dan `se-colophon.md` (dapat disunting langsung). Teks berasal dari OCR (TurboOCR), bukan dari ketik ulang.
- Naskah dibaca langsung dari `book.md`; edisi ini dibangun ulang dengan `pipeline.py --steps se`.
- Koreksi OCR hanya pada kesalahan yang jelas (pemeriksa ejaan SymSpell, ditinjau manual). Ejaan lama dan tidak baku dari narasumber dipertahankan.
- Kutip lurus dan kutip tunggal diubah menjadi kutip lengkung ganda sesuai manual SE; titik dan koma ditaruh di dalam tanda kutip.
- Singkatan ditulis tanpa titik sesuai kaidah Indonesia dan ditandai z3998:acronym; aturan lint s-023 (kapitalisasi judul gaya Inggris) tidak berlaku untuk bahasa Indonesia.
- Edisi white-label, bukan rilis Standard Ebooks: tanpa logo atau klaim SE. Halaman lisensi menggantikan Uncopyright SE karena teks sumber tidak berada di domain publik.
- Label navigasi (Daftar Isi, Penanda, Halaman Judul) diterjemahkan setelah `se build`; sumber tetap sesuai SE agar `se lint` lolos.
- Dua tabel Lampiran dipindai miring dan dibaca ulang dengan OCR diputar 180 derajat; isinya sebagian masih tidak terbaca dan dipertahankan apa adanya sesuai hasil OCR.
- Tabel stempel perpustakaan pada halaman judul (Koleksi Buku Perpustakaan Divisi Informasi dan Dokumentasi) dipertahankan di halaman sumber sebagaimana terbaca OCR, termasuk salah baca.
- Sampul sengaja dibuat sampul tipografi polos 1400 x 2100 (huruf League Spartan bawaan alat SE), bukan lukisan. Panduan sampul Standard Ebooks mensyaratkan lukisan cat minyak berwarna yang terbukti domain publik AS dan disetujui editor SE; edisi ini tidak memiliki karya seperti itu dan bukan rilis Standard Ebooks.
- Subjek LCSH dipilih dari id.loc.gov (Torture, Police brutality, Confession (Law), Criminal procedure--Indonesia, Human rights--Indonesia); belum ditinjau editor.
- Tanda baca dan awal paragraf yang tampak janggal bagi se lint (titik diikuti huruf kecil, paragraf terpotong halaman, kutipan) berasal dari hasil OCR atau naskah sumber. Karena pindaian tidak boleh diperiksa dengan penglihatan, teks tidak diubah; peringatan tinjau-manual didaftarkan di se-lint-ignore.xml dengan alasan masing-masing.
- Catatan kaki di akhir halaman pindaian dipindahkan menjadi catatan akhir (bagian Catatan di akhir tiap bab). Semua 60 catatan (bab I: 26, bab IV: 30, bab V: 4) ditautkan dua arah dengan penandanya di teks. Penandanya semula hilang atau terbaca keliru oleh OCR pada banyak catatan; pasangan catatan dan penanda ditetapkan penyunting secara manual pada naskah. Pada edisi SE, catatan dikumpulkan di halaman Catatan di akhir buku dan dinomori ulang menurut urutan kemunculan di teks.
- Nomor butir daftar bernomor (mis. 1. sampai 9. pada tugas kepolisian) tetap sebagai paragraf biasa; sebuah daftar yang terpotong halaman pindaian digabung ke catatan 5 (daftar tugas kepolisian menurut UU No. 13 Tahun 1961).
