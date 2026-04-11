# aith-asr-1st-group-proj-numbers
Repo for 1st group project for Itmo Speech Course


## Структура проекта

```text
asr-challenge/
│
├── dev/                                # аудиофайлы для валидации
├── test/                               # аудиофайлы для теста
├── train/                              # аудиофайлы для обучения
│
├── precomputed_features/               # MFCC-признаки (предвычисленные)
├── processed/                          # подготовленные данные (метаданные)
│
├── asr_analysis.ipynb                  # ноутбук с анализом и подготовкой данных
│
├── dev.csv                             # метаданные валидации
├── test.csv                            # метаданные теста
├── train.csv                           # метаданные обучения
├── sample_submission.csv               # пример сабмита
│
└── tokenizer.pkl                       # токенизатор

