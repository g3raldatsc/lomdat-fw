# Upgrade pip ke Versi Terbaru

Sebelum melakukan install library2 data science, pastikan untuk melakukan tahapan ini terlebih dahulu.

1. Buka terminal dan pastikan venv sudah aktif.
2. Ketik perintah: `python -m pip install --upgrade pip`
3. pip berhasil diuprade, bisa dilakukan install library2 data science.

# Install Library Data Science (Umum)

Lakukan tahapan ini jika sudah upgrade pip ke versi terbaru.

1. Buka terminal dan pastikan venv sudah aktif.
2. Ketik perintah: `pip install (nama library2 yang ingin diinstall)`.
3. Paling umum: `pip install numpy pandas matplotlib seaborn jupyter ipykernel scikit-learn xgboost lightgbm`.

# Membuat Requirement untuk Library yang Telah Diinstall

Tahapan ini dilakukan dengan maksud agar kedepannya untuk menginstall library lebih cepat menggunakan `pip install -r requirements.txt` di proyek yang lain.

1. Buka terminal, pastikan venv sudah aktif, dan pastikan library2 sudah dinstall.
2. Ketik perintah: `pip freeze > requirements.txt`.