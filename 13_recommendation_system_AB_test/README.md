# A/B тестирование рекомендательной системы

## Задача 
Оценить результаты A/B тестирования изменений, связанных с внедрением улучшенной рекомендательной системы

## Используемые библиотеки и инструменты
Pandas, Matplotlib, Plotly, Seaborn, SciPy

## Данные 
TODO



## Выводы
- A/B тест нельзя считать успешным по следующим причинам:
  - Несмотря на то, что общая аудитория теста составляет более 6000 участников, активными (совершившими хотя бы 1 действие) оказались только 52%
  - После отделения активных пользователей, распределение участников и событий в группах стало неравномерным: в коньрольной группе участников и событий больше
- Рекомендательная система могла оказать влияние на поведение пользователей только в случае просмотра карточки товара
- Ожидаемый результат не достигнут: конвесрия пользователей не повысилась ни для одного из указанных событий
