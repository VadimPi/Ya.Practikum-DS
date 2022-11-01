## Описание проекта и задача
Из данных пользователей телеком компании необходимо построить модель машинного обучения, которая будет предсказывать перестанет пользоваться клиент услугами или нет
(для дальнейшего предложения скидок/промокодов). главная метрика - это AUC-ROC

## Данные:
Таблицы со следующими данными:

contract.csv — информация о договоре;
personal.csv — персональные данные клиента;
internet.csv — информация об интернет-услугах;
phone.csv — информация об услугах телефонии.

## Стек 
Pandas, Numpy, Matplotlib, Sklearn, LightGBM, Optuna, Time

№№ Результат
Обучена модель LGBMClassifier. Итоговый результат (на тестовой выборке): 0.9135 AUC-ROC