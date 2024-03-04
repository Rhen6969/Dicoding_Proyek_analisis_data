# Dicoding_Proyek_analisis_data

## Analisis menggunakan Jupyter notebook
For more details: [Notebook](https://github.com/Rhen6969/Dicoding_Proyek_analisis_data/blob/main/Notebook.ipynb)

### Menentukan Pertanyaan Bisnis
- Apa pengaruh cuaca terhadap jumlah pengguna sepeda?
- Bagaimana pola peminjaman sepeda dalam sehari?
- Bagaimana pola peminjaman sepeda setiap hari dalam seminggu?
- Pada musim apa peminjaman sepeda paling tinggi?
- Bagaimana perbandingan tren penggunaan sepeda dalam setahun pada tahun 2011 dan 2012?

### Insights
- Cuaca mempengaruhi jumlah pengguna sepeda secara signifikan. Jumlah pengguna sepeda jelas lebih tinggi ketika cuaca cerah/sedikit berawan. Penggunaan sepeda ketika hujan dan cuaca buruk seperti badai berkurang secara signifikan.
- Untuk pengguna register, peminjaman sepeda meningkat pada pukul 8 dan 17, ini menimbulkan asumsi bahwa pengguna register menggunakan sepeda untuk pergi bekerja. Sedangkan, untuk pengguna casual, peminjaman meningkat di siang hari dan menurun memasuki sore hari pukul 17.
- Untuk pengguna register, jumlah peminjaman lebih tinggi pada hari kerja dibanding akhir pekan. Ini menguatkan asumsi sebelumnya bahwa pengguna register menggunakan sepeda untuk pergi bekerja. Sedangkan, untuk pengguna casual, jumlah peminjaman lebih tinggi pada akhir pekan, menunjukkan bahwa mereka menggunakan sepeda untuk bersantai.
- Peminjaman sepeda paling tinggi ada pada musim panas, dan terendah pada musim dingin.
- Pengguna sepeda tahun 2012 lebih tinggi daripada tahun 2011. Keduanya menunjukkan tren musiman yang sama ketika jumlahnya meningkat di pertengahan tahun dan mengalami penurunan di awal dan akhir tahun.

## Dashboard streamlit.app
visit: https://bike-sharing-masihpemula.streamlit.app

### Run streamlit locally
Buka terminal/command prompt pada komputer kemudian install library yang diperlukan:

```bash
pip install -r requirements.txt
```

#### Run Dashboard
```bash
cd dashboard
streamlit run dashboard.py
```

#### Or follow this instead and use VScode like I did 
https://docs.streamlit.io/get-started/installation/anaconda-distribution
