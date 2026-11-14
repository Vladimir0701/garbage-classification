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

Ноутбук рассчитан на запуск в Google Colab, среда с GPU T4 выбирается автоматически.

1. Открыть ноутбук в Colab: [ссылка](https://colab.research.google.com/github/Vladimir0701/garbage-classification/blob/main/garbage_classification.ipynb).
2. Запустить все ячейки (Среда выполнения → Выполнить все).

Датасет скачивается с Kaggle прямо в ноутбуке через `kagglehub`, вручную загружать ничего не нужно.

## Результаты

Заполняется после обучения модели.
