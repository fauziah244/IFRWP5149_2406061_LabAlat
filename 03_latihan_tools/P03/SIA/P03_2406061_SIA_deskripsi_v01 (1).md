|       Elemen        |                      SIA-UC01 — Ajukan KRS                       |
|---------------------|------------------------------------------------------------------|
|       Tujuan        |            Menghasilkan pengajuan KRS yang tersimpan             |
|     Aktor_utama     |                            Mahasiswa                             |
|  Sumber_kebutuhan   |                       SIA-R03 dan SIA-R04                        |
|       Pemicu        |              Mahasiswa memilih fungsi pengajuan KRS              |
|      Prasyarat      |    Mahasiswa telah terautentikasi; data mata kuliah tersedia     |
|Pascakondisi_berhasil|Pengajuan tersimpan dengan status Menunggu Persetujuan Dosen Wali |
| Pascakondisi_gagal  |         Tidak ada pengajuan baru yang berhasil tersimpan         |
|       Include       |                     SIA-UC02 — Validasi KRS                      |
|   Extension_point   |              Konfirmasi penyimpanan, pada langkah 8              |
|       Extend        |          SIA-UC03 jika [mahasiswa memilih unduh bukti]           |