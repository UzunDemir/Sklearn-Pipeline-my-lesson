# Sklearn-Pipeline-my-lesson

## Sklearn Pipeline - как я однажды разобрался с ним

---

"Sklearn pipeline - как я однажды разобрался с ним!"
---


Это была практическая работа по созданию пайплайна. Был блокнот с готовым рабочим кодом. И задача,похожая на ту, что в блокноте. Казалось бы, что тут такого - взять и перевести все на пайтон, глядя на готовый ноутбук. Но я этого сделать не смог, промучавшись долгих 2 дня! Чего только я ни делал, но мой пайплайн не работал! Тогда я решил конкретно разобрать эту тему, что это за pipline, как они работают.


![Вынос мозга](https://user-images.githubusercontent.com/94790150/217045456-06067f6e-ccd3-44bf-82c5-f99cb78ed010.png)

*"Вынос мозга" - картинка, сгенерированная нейросетью. Оригинал взят [из теграмм-канала @ai_drowing](https://web.telegram.org/z/#-1664452970)*

Изучить этот вопрос я решил вот на [этом примере.](https://inria.github.io/scikit-learn-mooc/python_scripts/01_tabular_data_exploration.html)

Мы будем использовать данные переписи населения США 1994 года, которые мы скачали с OpenML .

Вы можете посмотреть веб-страницу OpenML, чтобы узнать больше об [этом наборе данных:](http://www.openml.org/d/1590) .

Набор данных доступен в виде файла CSV (значения, разделенные запятыми), и мы будем использовать pandasего для чтения.

Хоть этот датасет оказался и не в формате csv, а в arff - это не страшно. Я его скачал в таком виде, потом залил на этот [сайт](https://pulipulichen.github.io/jieba-js/weka/arff2csv/), конвертировал и скачал готовый датасет в csv.

Вот здесь готовый [ноутбук](https://github.com/UzunDemir/Sklearn-Pipeline-my-lesson) с датасетом, можно взять и все пошагово выполнить и изучить.

А [вот здесь](https://github.com/INRIA/scikit-learn-mooc/tree/main/datasets) еще несколько датасетов для изучения, в том числе и в рамках этой статьи.

Скачивать любые файлаы можно через [github.dev](https://github.dev/INRIA/scikit-learn-mooc/blob/main/datasets/house_prices.csv)

Конвейеры (pipeline) можно не только создавать, но и [визуализировать!](https://scikit-learn.org/stable/auto_examples/miscellaneous/plot_pipeline_display.html#displaying-a-pipeline-chaining-multiple-preprocessing-steps-classifier)
