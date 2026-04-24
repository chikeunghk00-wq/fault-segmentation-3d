# fault-segmentation-3d
# Выделение разломов по 3D сейсмическим данным

DS'26 hackathon, geomodel.ru

## Результаты

| Модель | Val Dice (TTA) | Параметры |
|--------|---------------|-----------|
| BasicUNet v3 | 0.8107 | 13.87M |
| BasicUNet-B | 0.8108 | 31.21M |
| SegResNet | 0.7984 | 18.79M |
| **Ансамбль** | **0.8147** | — |

## Файлы

- `fault-segmentation-3d.ipynb` — ноутбук с инференсом и метриками
- `report.md` — описание подхода

## Данные и чекпоинты

- Датасет: [malik9/synth-seis-data](https://www.kaggle.com/datasets/malik9/synth-seis-data)
- Чекпоинты: [chikeung/block3-swin-ckpts](https://www.kaggle.com/datasets/chikeung/block3-swin-ckpts)
