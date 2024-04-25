# Конвейер машинного обучения

Проект представляет собой простой конвейер для автоматизации работы с моделью машинного обучения. Он состоит из нескольких этапов, каждый из которых описывается в отдельном Python-скрипте.

## Этапы работы

1. **data_creation.py**: Этот скрипт создает различные наборы данных для обучения и тестирования модели. Наборы данных могут содержать аномалии или шумы. Часть данных сохраняется в папке "train", а другая часть в папке "test".

2. **model_preprocessing.py**: Этот скрипт выполняет предварительную обработку данных перед обучением модели. В текущей реализации используется `StandardScaler` из библиотеки `scikit-learn` для стандартизации данных.

3. **model_preparation.py**: В этом скрипте создается и обучается модель машинного обучения на данных из папки "train". В нашем примере используется линейная регрессия из библиотеки `scikit-learn`.

4. **model_testing.py**: Этот скрипт проверяет производительность обученной модели на данных из папки "test" и выводит оценку качества модели.

## Запуск конвейера

Чтобы запустить конвейер машинного обучения, выполните bash-скрипт `pipeline.sh`

```bash
bash pipeline.sh
```
#   m l o p s _ h w 1  
 