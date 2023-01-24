
![](./images/data_cleaning.png)
# <center> Анализ резюме с сайта hh.ru </center>
## Оглавление
1. [Описание проекта](#Описание-проекта)
2. [Описание данных](#Описание-данных)
3. [Установка проекта](#Установка-проекта)
4. [Использование проекта](#Использование-проекта)
5. [Авторы](#Авторы)
6. [Выводы](Использование-проекта)

## Описание проекта
Часть соискателей не указывают желаемую заработную плату, когда составляют своё резюме. Это является помехой, для рекомендательной системы *headhunter*, котороя подбирает список наиболее подходящих вакансий, а работодателям список наиболее подходящих специалистов.

В проекте реализуется преобразование и предобработка данных базы резюме с сайта hh.ru, для модели машинного обучения, которая автоматически определяет примерный уровень заработанной платы, подходящий пользователю, исходя из информации, которую он указал о себя.

Основные этапы:
* Базовый анализ структуры данных.
* Преобразование данных.
* Разведывательный анализ.
* Очистка данных.

**Цель** — преобразовать, исследовать и очистить данные, для построения успешной модели машинного обучения. 

![](./images/example_outliers.png)

**О структуре проекта:**
* [data](./data) - папка с исходными табличными данными
* [images](./images) - папка с изображениями, необходимыми для проекта
* [outliers_lib](./outliers_lib) - папка со вспомогательными модулями для обработки выбросов 
* [data_cleaning_example.ipynb](./data_cleaning_example.ipynb) - jupyter-ноутбук, содержащий основной код проекта, в котором демонстрируются методы и подходы решения задач очистки данных

## Описание данных
В этом проекте используется база резюме, с сайта поиска вакансий hh.ru [датасет](https://drive.google.com/file/d/1AWK1-v4crqzL9FH3EPNaYet01dazbvSL/view?usp=share_link).

Исходный датасет представляет собой набор данных из таблицы с резюме соискателей. 

## Установка проекта

```
git clone https://github.com/Mahagry/ResumeAnalysisProject
```

## Использование
Вся информация о работе представлена в jupyter-ноутбуке - Project-1. Ноутбук-шаблон.ipynb
## Авторы

* [Сергей](https://vk.com/id474858221)

## Выводы

Допишите выводы по проделанной работе.