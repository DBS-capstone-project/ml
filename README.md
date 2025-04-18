# Mood & Emotion Classification Project

Proyek ini bertujuan untuk mengklasifikasikan emosi dari teks refleksi diri harian menggunakan pendekatan Machine Learning dan Deep Learning. Aplikasi ini dapat digunakan untuk mood tracking, deteksi distress, serta memberikan insight reflektif kepada pengguna.

## Dataset

Dataset utama terdiri dari berbagai ekspresi reflektif yang sudah dikategorikan ke dalam enam label emosi:
- **Anger**
- **Fear**
- **Joy**
- **Love**
- **Neutral**
- **Sad**

File: `final_fix_V2_merged_emotion_dataset.csv`  
Format: `\t`-delimited dengan dua kolom utama:
- `Tweet`: teks refleksi atau ekspresi pengguna
- `Label`: emosi yang dikaitkan dengan teks tersebut

## Jalankan

1. **Install dependency:**

```bash
pip install -r requirements.txt
```

2. **Run the Notebook with your Platform**

3. **Run the Notebook with your Platform**

```bash
uvicorn serv:app --host 0.0.0.0 --port 8080
```

## Akses
http://IP_OR_DOMAIN_SERVER:8080
