# Анализ резюме из HeadHunter
Учебный проект по окончании первого семестра программы "Науки о данных" МФТИ.
Цель проекта - анализ данных о резюме на HeadHunter.

## Описание
Проект состоит из четырёх частей:
1) базовый анализ структуры данных
2) преобразование данных
3) разведывательный анализ
4) очистка данных

Каждая часть состоит из блока практических заданий, которые выполняются в jupyter-ноутбуке с указанными требованиями.

## Зависимости
Проект написан на Python 3.12.1 с использованием библиотек:
* numpy
* pandas
* plotly

Использованные при работе датасеты:
* [основной датасет, содержащий информацию о резюме на HeadHunter](https://drive.google.com/file/d/1X-6UV3qiK3-E7s-VoiXmLx6ZRmwsMCch/view?usp=sharing)
* [датасет с курсами валют, использующийся для перевода желаемой заработной платы в рубли](https://drive.google.com/file/d/1nGzDKoEg3kK3hfYXuOLG3UY1urFrDC5z/view?usp=sharing)

## Plotly
GitHub не поддерживает отображение интерактивной визуализации в plotly. Результаты визуализации, выполненной с помощью plotly, представлены в [папке](plotly)

## Выводы
В ходе выполнения проекта данные в датасете были преобразованы к более удобному для работы с ними виду, был проведён разведывательный анализ данных с помощью визуализации, и данные были очищены от обнаруженных выбросов и пропусков.
