# Sudoku Solver C++

Repositori ini berisi implementasi *solver* Sudoku dalam bahasa C++. Kode ini menyelesaikan teka-teki Sudoku menggunakan algoritma *backtracking* yang cukup efisien.

## Fitur

*   Menyelesaikan teka-teki Sudoku 9x9.
*   Implementasi algoritma *backtracking* yang ringkas dan efisien.
*   Output ke konsol yang bersih (hanya menampilkan grid awal dan solusi akhir).
*   Kode yang mudah dipahami dan dimodifikasi.
*   Tidak ada ketergantungan pada *library graphics* eksternal (seperti SFML).

## Cara Menggunakan

1.  **Kompilasi:**

    Buka terminal atau *command prompt* Anda dan navigasi ke direktori tempat Anda menyimpan file `sudoku.cpp`. Gunakan *compiler* C++ (seperti g++) untuk mengkompilasi kode:

    ```bash
    g++ -o sudoku sudoku.cpp
    ```

2.  **Jalankan:**

    Setelah kompilasi berhasil, jalankan *executable* yang telah dibuat:

    ```bash
    ./sudoku
    ```

    Program akan menampilkan grid Sudoku awal dan solusi akhirnya (jika ada) ke konsol.

## Contoh Grid Sudoku

Kode ini menggunakan grid Sudoku berikut sebagai contoh:

5 3 0 0 7 0 0 0 0
6 0 0 1 9 5 0 0 0
0 9 8 0 0 0 0 6 0
8 0 0 0 6 0 0 0 3
4 0 0 8 0 3 0 0 1
7 0 0 0 2 0 0 0 6
0 6 0 0 0 0 2 8 0
0 0 0 4 1 9 0 0 5
0 0 0 0 8 0 0 7 9


di mana `0` merepresentasikan sel kosong.

## Struktur Kode

*   `sudoku.cpp`: Berisi kode sumber C++ untuk *solver* Sudoku.
*   `README.md`: File ini (berisi informasi tentang repositori).

## Fungsi-fungsi Utama

*   `is_valid(grid, row, col, num)`: Memeriksa apakah penempatan angka `num` pada baris `row` dan kolom `col` valid.
*   `solve_sudoku(grid, initial_grid)`: Menyelesaikan teka-teki Sudoku menggunakan algoritma *backtracking*.
*   `print_grid(grid)`: Mencetak grid Sudoku ke konsol.

## Kontribusi

Kontribusi dipersilakan! Jika Anda menemukan *bug* atau memiliki ide untuk perbaikan, silakan buat *issue* atau *pull request*.

## Lisensi

Kode ini didistribusikan di bawah Lisensi MIT. Lihat file `LICENSE` untuk informasi lebih lanjut.

## Ucapan Terima Kasih

Terima kasih kepada semua yang telah berkontribusi pada pengembangan *solver* Sudoku ini.

## Kontak

Jika Anda memiliki pertanyaan atau saran, Anda dapat menghubungi saya di [alamat email Anda].
