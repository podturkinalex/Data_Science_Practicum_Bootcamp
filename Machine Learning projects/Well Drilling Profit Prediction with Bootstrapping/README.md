# Выбор локации для скважины
## Подходы и инструменты

* **Разработка бизнес-модели**: `python`, `pandas`, `bootstrap`, `seaborn`, `histogram`, `boxplot`, `swarmplot`, `LinearRegression`.  

**Цель**
* Выбрать наиболее перспективное местонахождение для добычи нефти нефтедобывающей компании.

**Задачи**
* Проанализировать объёмы запасов в трёх регионах.
* Предсказать прибыль по 200 точкам и оценить риски, выбрать лучший регион, используя технику ` Bootstrap`. 

# Содержание
1. Загрузка и подготовка данных
    1.  Вывод
2. Подготовка данных к обучению
    1. Регион_0
    2. Регион_1
    3. Регион_2
    4. Вывод
3. Обучение и проверка модели
    1. Регион_0
    2. Регион_1
    3. Регион_2
    4. Общий вывод по построению моделей
4. Подготовка к расчёту прибыли
    1. Функция расчёта прибыли по выбранным скважинам и предсказаниям модели
    2. Вывод
5. Расчёт прибыли и рисков
    1. Регион_0
    2. Регион_1
    3. Регион_2
6. Общий вывод по построению моделей


**Описание данных**

*Данные проб нефти в трёх регионах.*

* `id` — уникальный идентификатор скважины;
* `f0`, `f1`, `f2` — три значимых признака для каждой из 10 тыс точек;
* `product` — объём запасов в скважине (тыс. баррелей).

*Данные о компании и цене продукции*
* Бюджет компании 10 млрд рублей.
* Cтоимость одной единицы продукции - 450 тыс рублей.

