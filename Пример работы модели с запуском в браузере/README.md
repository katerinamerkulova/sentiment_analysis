# Инструкция по запуску:

Сохранить папку на компьютер

Для работы необходима библиотека Flask:

$ pip install flask

Для запуска демо:

1. Введите в командную строку

$ python run_me.py

2. Откройте в браузере страницу:

http://127.0.0.1:5000/

Что еще в этой папке:

Скриншоты - примеры работы модели

model.ipynb - ноутбук с обучением модели

model.pickle - сохраненная обученная модель (больше 25 мб https://yadi.sk/d/q3PlO3zSAS3Jng)

reviews.csv - обучающая выборка (больше 25 мб https://yadi.sk/d/0Ush18N8YBiRCg)

sentiment_analysis.py - модуль, аналогичный sentiment_analysis.ipynb с соответствующими фукциями парсинга (сбора данных), обучения модели и предсказания по новым данным 

test.ipynb - ноутбук для проверки запуска работы модели по новым данным с использованием модуля sentiment_analysis.py
