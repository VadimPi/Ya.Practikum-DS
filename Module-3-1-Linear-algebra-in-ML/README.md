# Описание проекта и задача
Из данных о клиентах страховой компании нужно разработать метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию,
но качество моделей машинного обучения не ухудшилось. необходимо обосновать почему не поменяется качество линейной регрессии на формулах.

## Данные:
Одна таблица с следующими данными:

Признаки:
- пол,
- возраст,
- зарплата застрахованного,
- количество членов его семьи
Целевой признак:
- количество страховых выплат клиенту за последние 5 лет

## Стек
Pandas, Numpy, Sklearn

## Результат
Теоретически и практически доказана возможность матричной трансформации данных клиентов без влияния на качество ML модели.
