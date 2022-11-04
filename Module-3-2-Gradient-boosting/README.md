## Описание проекта и задача
Из исторических данных сервиса по продаже автомобилей с пробегом нужно построить модель для определения рыночной стоимости автомобиля клиента.
Заказчику важны: качество предсказания; скорость предсказания; время обучения.

## Данные:
Одна таблица с следующими данными:

Признаки
- DateCrawled — дата скачивания анкеты из базы
- VehicleType — тип автомобильного кузова
- RegistrationYear — год регистрации автомобиля
- Gearbox — тип коробки передач
- Power — мощность (л. с.)
- Model — модель автомобиля
- Kilometer — пробег (км)
- RegistrationMonth — месяц регистрации автомобиля
- FuelType — тип топлива
- Brand — марка автомобиля
- NotRepaired — была машина в ремонте или нет
- DateCreated — дата создания анкеты
- NumberOfPictures — количество фотографий автомобиля
- PostalCode — почтовый индекс владельца анкеты (пользователя)
- LastSeen — дата последней активности пользователя
Целевой признак
- Price — цена (евро)

## Стек
Pandas, Numpy, Matplotlib, Sklearn, LightGBM, Optuna, Time
 
## Результат
Подобрана модель LiteGBMRegressor с лучшим RMSE (1441,85) и результатом подбора параметров, обучения и предсказания (33.856510	6.010502	3.109500 ms)