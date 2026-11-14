# Классификация мусора по фото

Курсовая работа по курсу Computer Vision.

## Задача

Классификация фотографий отходов на 6 классов: картон, стекло, металл, бумага, пластик, прочее.

## Данные

[Garbage Classification на Kaggle](https://www.kaggle.com/datasets/asdasdasasdas/garbage-classification)

## Модель

MobileNetV2 с предобученными весами ImageNet, [статья](https://arxiv.org/abs/1801.04381).

## Структура проекта

```
garbage-classification/
├── garbage_classification.ipynb   # основной ноутбук
├── requirements.txt
├── report/                        # отчёт
└── README.md
```

## Запуск

Ноутбук рассчитан на запуск в Google Colab с GPU.

1. Открыть `garbage_classification.ipynb` в Colab.
2. Загрузить датасет (`archive.zip` с Kaggle) либо примонтировать Google Drive.
3. Запустить ячейки по порядку.

## Результаты

Заполняется после обучения модели.
