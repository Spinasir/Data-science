**Прогнозирование оттока клиента Банка**

`Pandas`, `Matplotlib`, `Scikit-learn`

Из банка стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.
Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Предоставлены исторические данные о поведении клиентов и расторжении договоров с банком.

**Вывод**

Мы изучили данные, провели их предобработку, изучили баланс классов выборки и построили модель для предсказания оттока клиентов.
Лучше всех на несбалансированных данных себя показала модель рандомного леса, с метрикой f1 = 0.640.
После устранения дисбаланса классов лучше всего себя показала модель рандомного леса на выборке c методом domnsampling: f1 = 0.625
