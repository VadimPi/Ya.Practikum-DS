## Описание проекта и задача
Из исторических данных сервиса по заказу такси нужно построить модель для прогноизрования количества заказов такси на слеудющий час.
Нужно подобрать оптимальные дополнительные признаки.

## Данные:
Одна таблица (времянной ряд) с следующими данными:

Признаки
- datetime - время (с точностью до 10 минут)
- Целевой признак
- num_orders - количество заказов
 
## Стек 
Pandas, Numpy, Matplotlib, Sklearn, LightGBM, Optuna, Statsmodel, Time

## Результат
Подобрана лучшая модель для нашего предсказания (RandomForestRegressor).
Она показала лучший RMSE (40,12).
Для моделей были созданы дополнительные признаки: Календарные (номер месяца, день месяца, день недели, час),
Сезонности (почасовая, подневная), добавлен тренд, средние скользящие и смещения.
