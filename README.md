<p align="center">
<img src="banner.png" alt="Banner" style="width:100%; height:auto;" />
</p>

<h1 align="center"><b>Materi dan Hands-on untuk TT25-31005</b></h1>

Repository ini berisi kumpulan materi dan hands-on untuk mata kuliah TT25-31005 Kecerdasan Buatan di Teknik Telekomunikasi, Institut Teknologi Sumatera ([ITERA](https://itera.ac.id)).

## Daftar Isi

| No. | Topik                             | Deskripsi                                                     | Notebook                                                                                                                          |
| --- | --------------------------------- | ------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| 1   | _CNN1D ECG Signal Classification_ | Deteksi Sinyal _Electrocardiogram_ Dengan Menggunakan _CNN1D_ | [CNN1D_ECG_Classification.ipynb](https://colab.research.google.com/drive/1l5vC-f3LDtFKthh1NY_TRmb08Xqp2fZ0#scrollTo=nuC6uN_JUtne) |
| 2   | Audio Classification              | Klasifikasi Audio Sederhana dengan Fitur Spectrogram          | [audio_classification.ipynb](audio_classification.ipynb)                                                                          |
| 3   | Face Mask Detection               | Deteksi Masker Wajah dengan _transfer learning_ YOLOv8        | [face_mask_detection_YOLOv8.ipynb](face_mask_detection_YOLOv8.ipynb)                                                              |

## Persiapan Environment (Sekali Saja)

Environment adalah “ruang kerja” terisolasi tempat Python dan kumpulan paket/dependensi disimpan sehingga tidak bercampur dengan proyek lain atau instalasi yang sudah ada di sistem operasi.

Pilih salah satu opsi di bawah ini.

Opsi A — venv (ringan dan standar):
- macOS/Linux (bash):
  ```bash
  python3 -m venv .venv
  source .venv/bin/activate
  pip install -r requirements.txt
  ```
- Windows (PowerShell):
  ```powershell
  python -m venv .venv
  .venv\Scripts\Activate
  pip install -r requirements.txt
  ```

Opsi B — Miniconda/Conda (mudah ganti versi Python):
```bash
conda create -n chestmnist python=3.10 -y
conda activate chestmnist
pip install -r requirements.txt
```

Opsi C — uv (cepat dan modern):
```bash
# Instal uv (macOS/Linux)
curl -LsSf https://astral.sh/uv/install.sh | sh

# Buat dan aktifkan environment
uv venv
source .venv/bin/activate  # macOS/Linux
# Windows PowerShell: .venv\Scripts\Activate

# Instal dependencies (sangat cepat)
uv pip install -r requirements.txt
```
