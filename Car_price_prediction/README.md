# Предсказание цены автомобиля


## Цель

Необходимо обучить модель для определения рыночной стоимости автомобиля. В нашем распоряжении следующие данные: технические характеристики, комплектации и цены автомобилей.

## Результат

* Данные были предобработаны на предмет пропусков и аномалий.
* Были обучены различные модели (Dropouts meet Multiple Additive Regression Trees, модель стохастического градиентного спуска, случайный лес с градиентным бустингом, линейная регрессия). 
* Наиболее быстрой в плане обучения является модель линейной регресии. Однако если выставить определенное количество итераций три других метода за то же время что и линейная регрессия дадут лучший результат.
* Среди моделей с градиентным бустингом наиболее быстро обучилась модель случайного леса, но при этом на большинстве итераций не происходило положительной динамики улучшения *RMSE*
* Самой медленной моделью, но при этом выдающей самый качественный результат является модель *DART*, при определенных параметрах и большом количестве итераций можно было получить *RMSE* < 1000.
* Стабильной и в плане скорости, и в плане улучшения *RMSE* показала себя модель *gbdt*.

## Используемые библиотеки
*pandas*, *sklearn*, *numpy*, *lightgbm*

## Статус проекта

Закончен.