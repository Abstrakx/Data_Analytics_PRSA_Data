# Data Analytics (Dicoding Final Submission) 💻🔥

Proyek ini bertujuan untuk menganalisis data kualitas air dari beberapa stasiun pengukuran di China. Data ini mencakup parameter seperti PM2.5, PM10, SO2, NO2, CO, dan O3, serta variabel-variabel lainnya yang berkaitan dengan kualitas Air.

## Dataset 

Proyek ini menggunakan dataset PRSA_Data_20130301-20170228 yang berisi catatan harian tentang kualitas udara yang diukur di beberapa stasiun pengukuran di China. Setiap catatan termasuk informasi tentang PM2.5, PM10, SO2, NO2, CO, dan O3, serta beberapa variabel lain seperti suhu, tekanan, dan kelembaban. Dataset ini dapat diakses melalui [PRSA_Data_20130301-20170228](https://drive.google.com/uc?id=1UjJJ1yboo9gFAU0rNgCSRxTsjqHe6gd3). 

Didalamnya terdapat 12 dataset dari kota yang berbeda-beda, akan tetapi yang kita gunakan hanya 4 yaitu :
* PRSA_Data_Aotizhongxin_20130301-20170228.csv
* PRSA_Data_Guanyuan_20130301-20170228.csv
* PRSA_Data_Shunyi_20130301-20170228.csv
* PRSA_Data_Wanshouxigong_20130301-20170228.csv

## Dependensi

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Streamlit
- Python virtual environment (venv)

## Cara menggunakan 
### 1. Pastikan anda membuat virtual environtment `.venv` di dalam folder ini.
```bash
$ python -m venv .venv
```

### 2. Aktifkan virtual environtment
Untuk MacOs dan Linux (Bash atau Zsh Shell)
```bash
$ source .venv/bin/activate
```
Untuk Windows Command Shell
```bash
$ ./.venv/Scripts/activate
```

### 3. Upgrade pip
```bash
(.venv) $ pip install pip --upgrade
```

### 4. Install  packages yang ada di file `requirements.txt`
```bash
(.venv) $ pip install -r requirements.txt
```

### 5. Masuk ke direktori dashboard
```bash
(.venv) $ cd dashboard
```

### 6. Jalankan streamlit
```bash
(.venv) $ streamlit run dashboard.py
```
### 7. Otomatis akan membuka browser dan steamlit sudah siap
Jika tidak terbuka sendiri, coba masukan ip yang ada diterminal ke browser.

## Catatan 
Tolong untuk .ipynb menggunakan colab. 

## Colaborator
Maulana Al Iqbal Widodo
