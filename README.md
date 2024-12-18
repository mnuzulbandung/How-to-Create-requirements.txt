# Membuat file requirement.txt berdasarkan aplikasi app.py

Untuk mendeploy aplikasi yang dibuat ke dalam Streamlit atau Docker, dibutuhkan file requirement.txt. File ini berisi library-library beserta versi-versinya yang dibutuhkan untuk menjalankan aplikasi tersebut.

### How to: Membuat file requirement.txt

1. Buka Anaconda Prompt; aktifkan virtual environment yang digunakan untuk menjalankan aplikasi; pergi ke folder aplikasi; jalankan script berikut untuk menginstall pipreqs.

   ```
   pip install pipreqs
   ```

2. Eksekusikan script berikut untuk membuat file requirement.txt di dalam folder yang sama.

   ```
   pipreqs . --force
   ```

### How to: Melihat versi python

1. Buka Anaconda Prompt; aktifkan virtual environment yang digunakan untuk menjalankan aplikasi; jalankan script berikut.

   ```
   python --version
   ```

Sumber: [geeksforgeeks](https://www.geeksforgeeks.org/how-to-create-requirements-txt-file-in-python/) dan [geeksforgeeks](https://www.geeksforgeeks.org/check-the-version-of-the-python-interpreter/)
