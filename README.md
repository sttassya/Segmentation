# Segmentation
# Сегментация, визуализация, снижение размерности данных. Сегментация рынка клиентов банка.
Выполнила: Кузнецова Анастасия 11-005.
# Видео с защитой проекта:
https://youtu.be/Z3uRzTOB-wM
# Датасет: 
https://www.kaggle.com/arjunbhasin2013/ccdata
Данный датасет содержит информацию о клиентах банка. 8950 экземпляров данных кредитной карты клиента.
Набор данных включает сумму баланса, колтичество покупок, кредитный лимит и многое другое.

Задача:
На основе данных сегментировать клиентов для маркетинговой стратегии.

Использованные методы:
KDE. График KDE - это непараметрический способ оценки функции плотности вероятности случайной величины.
Elbow Method. Метод состоит в построении графика объясненной вариации в зависимости от количества кластеров и выборе локтя кривой в качестве количества кластеров для использования.
K-Means. Метод K-средних– это метод кластерного анализа, целью которого является разделение m наблюдений на k кластеров, при этом каждое наблюдение относится к тому кластеру, к центроиду которого оно ближе всего.
Pricipal Component Analysis. Cпособ уменьшить размерность данных, потеряв наименьшее количество информации.

# Вывод
Получилось сегментировать 4 класса клиентов.	
	Первая группа клиентов. Это клиенты, которые платят наименьшую сумму процентов и бережно относятся к своим деньгам, Кластер с самым низким балансом и выдачей наличных, с высоким процентом от полной оплаты.
	Вторая группа. Люди, которые используют кредитную карту в качестве кредита (наиболее прибыльный сектор).Люди с самым высоким балансом и выдачей наличных, низкой частотой покупок, высокой частотой выдачи наличных, большим количеством транзакций по выдаче наличных и низким процентом от полной оплаты.
	3 группа. Люди, которые имеют высокий кредитный лимит и самый высокий процент полной оплаты, нацелены на увеличение кредитного лимита.
	4 группа. Это клиенты с низким сроком владения, низким балансом.
