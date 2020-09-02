# Очистка золотосодержащей руды


## Цель

Необходимо обучить модель для предсказания коэффициента восстановления золота из золотосодержащей руды. В нашем распоряжении данные с параметрами добычи и очистки.

## Результат

* Данные были предобработаны, пропуски заполнены, аномалии удалены c метода *IsolationForest*.
* Визуализирован процесс увеличения/уменьшения концентрата разных металлов после каждой стадии очистки.
* Была написана функция вычисления ошибки *sMAPE*.
* Лучшая модель - случайный лес со случайным подбором гиперпараметров.

## Используемые библиотеки
*pandas*, *math*, *sklearn*, *numpy*, *seaborn*, *matplotlib*

## Статус проекта

Закончен.