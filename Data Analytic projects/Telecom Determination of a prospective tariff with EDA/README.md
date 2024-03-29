# Определение перспективного тарифа для телеком компании


### Подходы и инструменты

**Предобработка данных**: `pandas`, `numpy`. Обработка данных, пропуски, форматы, названия столбцов, объединение таблиц, расчёты и добавление результатов в таблицу.

**EDA и статистический анализ**: `pandas`, `scipy`, `matplolib`, `seaborn`: `pivot_table`, `histogram`, `barplot`, `Donut Plot`, `boxplot`, `subplots`, `pairplot`, `heatmap` `corr`, `kstest`, `mannwhitneyu`.


**Цель**
* Определить какой тариф приносит больше денег - `Смарт` или `Ультра`.


**Задача**
* Провести описательный и статистический анализ данных о поведении 500 пользователей тарифов `Смарт` или `Ультра` и выявить наиболее выгодных тариф.

**Мои усилия**
* В этом проекте мне было интересно разобраться с анализом поведения пользователей между тарифами. Я старался использовать разные способы визуализации для построения гипотез и грамотно применять статистические тесты под распределения конкретных выборок. 

**Описание данных**
* Информация о 500 клиентов за 2018 год. 

* Есть четыре таблицы (`users`, `calls`, `messages`, `internet`, `tariffs`) о пользователях и использования ими двух тарифов при отправке сообщений, звонков, использовании интернета и информация о тарифах

* Описание тарифов приведены внутри тетрадки.


# Содержание
1. Знакомство с данными
    1. Вывод
2. Предобработка данных
     1. Звонки
     2. Сообщения
     3. Интернет
     4. Создание единой таблицы по клиентам
     5. Вывод    
3. Расчёты и добавление результатов в таблицу
    1. Вывод
4. EDA
    1. Выручка по клиентам в зависимости от тарифа
    2.  Вывод
    3.  Поведение пользователей: звонки и их количество / сообщения / интернет-трафик/ возраст
    4.  Вывод   
5. Проверка гипотез
    1. Гипотеза №1: Выручка между тарифами
    2. Гипотеза №2: средняя выручка пользователей из Москвы отличается от выручки пользователей из других регионов.
    3.  Гипотеза №3: средняя продолжительность звонка пользователей тарифов «Ультра» и «Смарт» различаются.
    4.  Гипотеза №4: средний объем интернет трафика тарифов «Ультра» и «Смарт» различается.
    5.  Гипотеза 5: среднее количество сообщений тарифов «Ультра» и «Смарт» различается.
6. Общий вывод  
