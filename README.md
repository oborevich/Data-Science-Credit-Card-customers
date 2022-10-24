# Data-Science-Credit-Card-customers
Практическая работа 1.

**Краткое описание датасета:** <br>
**Credit Card customers** – набор данных, состоящий из 10 000 клиентов американского банка и содержащий их следующие данные: возраст, зарплату, семейное положение, лимит кредитной карты, категорию карты и др. <br>

Всего исходный датасет содержит <font color = blue> 10 127 наблюдений </font> и <font color = blue> 23 переменных (категории/столбца)</font>.

Автор датасета: Sakshi Goyal<br>
Источник: [Kaggle](https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers)

**Условные обозначения исходного датасета:**<br>
1. **CLIENTNUM** – Номер клиента
2. **Attrition_Flag** – Статус клиента (текущий/бывший)
3. **Customer_Age** – Возраст клиента
4. **Gender** – Пол клиента
5. **Dependent_count** – Количество иждивенцев (детей)
6. **Education_Level** – Уровень образования
7. **Marital_Status** – Семейное положение
8. **Income_Category** – Уровень дохода
9. **Card_Category** – Категория/уровень карты 
10. **Months_on_book** – Продолжительность взаимодействия с банком (мес.)
11. **Total_Relationship_Count** – Количество продуктов/услуг банка, которыми пользуется клиент
12. **Months_Inactive_12_mon** – Количество неактивных месяцев за последний год (12 мес.)
13. **Contacts_Count_12_mon** – Количество взаимодействий с банком за последний год (12 мес.)
14. **Credit_Limit** – Лимит по кредитной карте (usd)
15. **Total_Revolving_Bal** – Общий возобновляемый остаток на кредитной карте (usd)
16. **Avg_Open_To_Buy** – Разница между кредитным лимитом, присвоенным счету владельца карты, и текущим балансом на счете за последний год (12 мес.)
17. **Total_Amt_Chng_Q4_Q1** – Изменение суммы транзакции/платежа (4 квартал по сравнению с 1 кварталом)
18. **Total_Trans_Amt** – Общая сумма транзакций/платежей за последний год (12 мес., usd)
19. **Total_Trans_Ct** – Общее количество транзакций за последний год (12 мес., шт.)
20. **Total_Ct_Chng_Q4_Q1** – Изменение количества транзакций (4 квартал по сравнению с 1 кварталом)
21. **Avg_Utilization_Ratio** – Средний коэффициент использования карты
22. **Naive_Bayes_Classifier_Attrition_Flag_Card_Category_Contacts_Count_12_mon_Dependent_count_Education_Level_Months_Inactive_12_mon_1** – Наивный байесовский классификатор (1)
23. **Naive_Bayes_Classifier_Attrition_Flag_Card_Category_Contacts_Count_12_mon_Dependent_count_Education_Level_Months_Inactive_12_mon_2** – Наивный байесовский классификатор (2)


**ЦЕЛЬ И ЗАДАЧИ ИССЛЕДОВАНИЯ**

**Цель** – содержательно проанализировать датасет, состоящий из информации о держателях кредитных карт американского банка, а также выявить связи между категориальными и количественными переменными.

**Задачи:**
1. Ознакомиться с датасетом и сделать его краткое описание с помощью базовых манипуляций (переименование столбцов, выявление пропусков и дублей и др.).
2. Перекодировать строковые переменные в категориальные.
3. Проанализировать выбросы и отклонения от среднего (методы: интерквартильный размах и 3 сигмы).
4. Провести EDA (описательные статистики, продвинутая визуализация).
5. Проверить выдвинутые гипотезы для категориальных (Хи-квадрат) и количественных переменных (корр.-регресс. анализ).
6. Сформулировать ключевые выводы и ограничения исследования.
