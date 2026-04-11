# aith-asr-1st-group-proj-numbers
Repo for 1st group project for Itmo Speech Course



## 📁 Структура проекта

asr-challenge/
|
├── data/                                 # Исходные данные (Kaggle)
|   ├── train.csv                         # метаданные обучающей выборки
|   ├── train/                            # аудиофайлы для обучения
|   ├── dev.csv                           # метаданные валидационной выборки
|   ├── dev/                              # аудиофайлы для валидации
|   ├── test.csv                          # метаданные тестовой выборки
|   ├── test/                             # аудиофайлы для теста
|   └── sample_submission.csv             # пример файла для сабмита
|
├── prepared_data/                        # ПОДГОТОВЛЕННЫЕ ДАННЫЕ (моя часть)
|   ├── features/                         # предвычисленные MFCC-признаки (.npy)
|   ├── train_metadata.csv                # метаданные train с текстами
|   ├── dev_metadata.csv                  # метаданные dev с текстами
|   ├── tokenizer.pkl                     # токенизатор русских слов
|   ├── fast_dataset.py                   # быстрый Dataset для загрузки
|   └── DATA_REPORT.md                    # детальный отчёт по данным
|
├── notebooks/                            # Jupyter ноутбуки
|   ├── 01_data_preparation.ipynb         # подготовка данных (моя часть)
|   └── 02_model_training.ipynb           # обучение модели (часть сокомандника)
|
├── models/                               # сохранённые модели
|   └── best_model.pth                    # лучшая модель после обучения
|
├── submissions/                          # файлы для отправки на Kaggle
|   └── submission.csv                    # результат для теста
|
├── requirements.txt                      # зависимости проекта
└── README.md                             # этот файл

