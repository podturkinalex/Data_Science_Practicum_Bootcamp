# Отток клиентов

## Подходы и инструменты

* **Предобработка**: `pandas`

* **EDA**: `scipy`, `matplotlib`, `seaborn`: `chi2_contingency`, `pointbiserialr`, `corr`, `pieplot`, `pairplot`, `heatmap`.

* **Построение классификационных моделей, подбор гиперапараметров, выбор модели, борьба с дисблансом классов**: `train_test_split`, ` One-Hot Encoding`, `StandardScaler`, `upsample`, `class_weight`, `SMOTE`, `LogisticRegression`, `DecisionTreeClassifier`, `RandomForestClassifier`, `GridSearchCV`, `classification_report`, `f1_score`, `roc_auc_score`, `roc_curve`. 

 
## Цель
* Спрогнозировать отток клиентов банка.

**Задача**
* Проанализировать исторические данные о поведении пользователей.
* Построить модель с `F1` метрикой не меньше 0,59.
* Дополнительно измерить значения `AUC-ROC`.


**Мои усилия**
* В этом проекте я дополнительно освоил методы корреляций как между количественными переменными, так и между качественным откликом и качественными/количественными признаками.
* Использовал разные техники с дисбалансом классов, включая `SMOTE`.
* Использовал разные техники для иллюстрации анализа данных и результатов алгоритмов машинного обучения.



**Описание данных**

*Признаки*
*	RowNumber — индекс строки в данных
*	CustomerId — уникальный идентификатор клиента
*	Surname — фамилия
*	CreditScore — кредитный рейтинг
*	Geography — страна проживания
*	Gender — пол
*	Age — возраст
*	Tenure — сколько лет человек является клиентом банка
*	Balance — баланс на счёте
*	NumOfProducts — количество продуктов банка, используемых клиентом
*	HasCrCard — наличие кредитной карты
*	IsActiveMember — активность клиента
*	EstimatedSalary — предполагаемая зарплата

**Целевой признак**
*	Exited — факт ухода клиента

Источник данных: [https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling](https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling)





# Содержание
1.  Знакомство и подготовка данных
    1. One-Hot Encoding
    2. Вывод
2. Анализ данных
    1. Корреляции
    2. Подготовка данных к обучению
    3.  Вывод    
3. Обучение моделей
      1. Модели с дисбалансом классов
            1. LogisticRegression
            2. DecisionTreeClassifier
            3. RandomForestClassifier
            4. Вывод  
      2. Борьба с дисбалансом классов
            1. LogisticRegression
            2. DecisionTreeClassifier
            3. RandomForestClassifier
            4. SMOTE
            5. Вывод   
4. Тестирование модели
5. Вывод
