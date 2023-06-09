![image](https://github.com/dmakhazen/portfolio/assets/107398428/850dd956-fa69-42d6-96aa-425ed0e0ceeb)

# EDA analysis games dataset

Результат:
- [Jupyter_notebook](https://github.com/dmakhazen/portfolio/tree/main/EDA_games/computer_games_EDA.ipynb)
- [Код в PDF](https://github.com/dmakhazen/portfolio/tree/main/EDA_games/computer_games_EDA.pdf)
- [Google Colab](https://colab.research.google.com/github/dmakhazen/portfolio/blob/main/EDA_games/computer_games_EDA.ipynb)

## Описание проекта

**Проблема** заключается в сложности прогнозирования динамичного рынка компьютерных игр. Необходимо провести исследование и обработку большого объема данных о продажах игр, чтобы выявить закономерности и тенденции, влияющие на успешность игровых платформ и жанров. Это поможет сделать выводы о том, какие платформы и жанры наиболее популярны, а также понять, как отзывы пользователей и критиков влияют на продажи игр.

**Цель работы** состоит в анализе данных о продажах компьютерных игр для определения успешности их выпуска на различных платформах и в разных регионах.

**Ожидаемые результаты:** Выявить наиболее успешные игровые платформы и жанры. Оценить влияние отзывов критиков и пользователей на продажи игр. Результаты исследования помогут понять предпочтения игроков и основные факторы, влияющие на коммерческий успех видеоигр.

## Ключевые особенности
- Отличная визуализация
- Тщательный анализ закономерностей и тендеций

## Инструменты, навыки

Инструменты:
- Pandas
- Matplotlib
- Seaborn
- Scipy

Навыки:
- Работа с табличными данными
- Статистический анализ
- Визуализация
- A/B тест

## Общий вывод
1. Рынок видоигр очень динамичный, платформы приходят и уходят, срок жизни около 6 лет, но первый и последний год из них это резкий подьем и резкое падение продаж. Стабильно платформы держаться около 4 лет. Поэтому при создании игр очень важно искать актуальную сейчас и в будущем платформу.
2. Регионы EU и NA похожи по потреблению игр, однако JP регион сильно другой, предпочитая дургие платформы, игры, жанры и аудитория (судя по рейтингу) другая, более молодая вероятно.
3. Жанры игр сильно отличаются по продажам. Action/Shooter на первом месте по сумме продаж. Паззлы и стратегии продаются на порядки меньше.
4. Какая платформа лучше по мнению пользователей, Xbox или PS? Статистически достовернного отличия нет. Хотя игры на PS продаются лучше чем на XBox.
5. Про прибыльность игр/платформы/жанров невозможно ничего сказать не зная затраты на разработку/маркетинг. Хотя есть множество игр которые продались миллионами копий, но были ли они прибыльными? Так же невозможно оценить прибыль от платформы. Однако если взять только общие продажи, то выпуск игры на PS будет более востребованным.
6. Жанры отличаются друг от друга не только количеством продаж, но и средней оценкой.
7. Очень интересная корреляция между рейтингом от пользователей и общими продажами. Её нет. Значит этот рейтинг для прогнозирования продаж не так и важен, в отличии от рейтинга критиков.
