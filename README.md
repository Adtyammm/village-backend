#  Cara menjalankan Village-be 

  untuk menginstal semua dependensi yang tercantum dalam file package.json
  # 1. npm i

#  DARI NO 2 - 6 PASTIKAN ANDA BERADA DI DIRECTORY FOLDER FLASK
   untuk menginstal virtual envirement
#  2. python -m venv venv

  untuk mengaktifkan virtual environment
#  3. .\venv\Scripts\activate

  untuk menginstal semua paket python yang digunakan
#  4. pip install flask torch transformers pandas scikit-learn

  dikarenakan dibutuhkan numpy versi 1.x.x maka kita harus menghapus numpy 2.x.xnya
#  pip uninstall numpy
#  pip install numpy==1.21.0


  untuk membuat model yang akan digunakan 
#  5. python train.py

  untuk menjalankan flask
#  6. python app.py

  untuk menjalankan backend
  #  7. nodemon index ( jika tidak bisa gunakan nodemon index.js)
