# Pembuatan Virtual Environment untuk Kompetisi

Berikut adalah tahapan untuk membuat virtual environment yang singkat dan jelas.

1. Buka terminal VSCode (**CTRL + J** atau **CTRL + SHIFT + `**).
2. Make sure kalau direktori udah sesuai untuk tempat venv (Folder Besar Perlombaan).
3. Ketik perintah: `python -m venv z_nama_venv` (Kenapa diawali z? agar posisi venv berada paling akhir).
4. Virtual Environment sudah berhasil dibuat.

# Mengaktifkan Virtual Environment

Berikut adalah tahapan untuk mengaktifkan virtual environment di terminal VSCode.

1. Di terminal, ketik perintah: `.\z_nama_venv\Scripts\Activate.ps1`.
2. Virtual Environment berhasil diaktifkan dengan tanda warna hijau atau muncul teks z_nama_venv.

# Menambahkan Virtual Environment sebagai kernel Jupyter

Ini adalah tahapan yang dijalankan ketika ingin menambahkan kernel jupyter untuk ngoding di ipynb.

1. Pastikan sebelum melakukan ini, jupyter dan ipykernel sudah diinstall (cek 2_install_library_datsc).
2. Pada terminal yang sudah aktif venv-nya, ketik perintah: `python -m ipykernel install --user --name=z_nama_venv --display-name "Python (z_name_venv)"`.
3. Kernel berhasil dibuat, silakan cek pada file .ipynb, lalu tekan select kernel, dan pilih kernel yang sudah dibuat tadi.

# Menonaktifkan Virtual Environment

Ini adalah tahapan yang dijalankan ketika ingin menonaktifkan venv.

1. Pada terminal, pastikan kondisi venv sedang aktif.
2. Ketik perintah: `deactive`.
3. Venv berhasil dinonaktifkan.