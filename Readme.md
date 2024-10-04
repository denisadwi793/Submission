# Bike Sharing Analysys Data
Repositori ini berisi analisis dashboard dataset bike sharing tahun 2011 dan 2012 dari sistem Capital Bikeshare, Washington D.C., Amerika Serikat.

## Features

- Visualisasi jam puncak penyewaan sepeda dalam satu minggu
- Visualisasi pengaruh cuaca terhadap penggunaan sepeda di hari bekerja
- Visualisasi pengaruh cuaca terhadap penggunaan sepeda di hari libur

## Setup Environment - Anaconda
```bash
    conda create --name main-ds python=3.9
    conda activate main-ds
    pip install -r requirements.txt
```

#### Setup Environment - Shell/Terminal
```bash
    mkdir proyek_analisis_data
    cd proyek_analisis_data
    pipenv install
    pipenv shell
    pip install -r requirements.txt
```

## Run steamlit app
```bash
streamlit run dashboard.py
```

