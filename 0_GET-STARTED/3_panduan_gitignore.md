Ini adalah panduan penting sebelum melakukan publish proyek data science ke repositori GitHub.

1. Buat file .gitignore yang setara posisinya pada direktori dengan Virtual Environment.
2. Pada file .gitignore, tempel hal sebagai berikut:

`# Virtual Environments (Mengabaikan folder environment)`

`z_nama_venv/1`

`.venv/`

`venv/`

`ENV/`

`env/`

`# Python cache & temporary files (File kompilasi Python)`

`__pycache__/`

`*.py[cod]`

`*$py.class`

`# Jupyter Notebook checkpoints`

`.ipynb_checkpoints/`

`# Settings & cache dari VS Code`

`.vscode/`

`# Environment Variables (File berisi password/API key jika ada)`

`.env`

Setelah itu, baru bisa dilakukan publish ke GitHub :3