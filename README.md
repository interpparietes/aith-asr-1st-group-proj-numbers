# aith-asr-1st-group-proj-numbers
Repo for 1st group project for Itmo Speech Course



---
asr-challenge/
├── data/ # Исходные данные (Kaggle)
│ ├── train.csv + train/ # обучающая выборка
│ ├── dev.csv + dev/ # валидационная выборка
│ └── test.csv + test/ # тестовая выборка
│
├── prepared_data/ # ПОДГОТОВЛЕННЫЕ ДАННЫЕ (моя часть)
│ ├── features/ # предвычисленные MFCC-признаки (.npy)
│ ├── train_metadata.csv # метаданные train с текстами
│ ├── dev_metadata.csv # метаданные dev с текстами
│ ├── tokenizer.pkl # токенизатор русских слов
│ ├── fast_dataset.py # быстрый Dataset для загрузки
│ └── DATA_REPORT.md # детальный отчёт по данным
│
├── notebooks/ # Jupyter ноутбуки
│ ├── 01_data_preparation.ipynb # подготовка данных (моя часть)
│ └── 02_model_training.ipynb # обучение модели (часть сокомандника)
│
└── README.md # этот файл

---

