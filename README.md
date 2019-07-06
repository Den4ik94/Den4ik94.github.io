# Интерактивное демо:

### Реализованы интерактивные графики фактических и прогнозируемых временных рядов через 1,2,3,4,5,6 часов при выборе географического региона из выпадающего списка.

![Иллюстрация к проекту](https://github.com/Den4ik94/memory/blob/master/Временные%20ряды.gif)

В рамках разработки моделей использовались следующие итерации:
1) Прогнозирование регрессионной компонеты случайным лесом (на кросс-валидации с помощью GridsearchCV выбиралась лучшая модель);
2) Прогнозирование остатков (факт - прогноз №1) с помощью Lasso-регрессии (лучшии параметры снова определялись на кросс-валидации);
3) Прогнозирование остатков остатков (факт - прогноз №1 - прогноз №2) с помощью авторегрессий - прежде все временные ряды были условно проверены на стационарнотсь критерием Дики-Фуллера.

Scoring на июне составил примерно 16.5

### Реализованы интерактивные карты фактического и прогнозируемого спроса на такси с двумя слайдерами: 
### - период времени (Time);
### - прогноза через ... часов (F);

![Иллюстрация к проекту](https://github.com/Den4ik94/memory/blob/master/Карты.gif)
![Иллюстрация к проекту](https://github.com/Den4ik94/memory/blob/master/Карты_2.gif)

На мой взгляд, данные картинки являются исчерпывающими :)
