# Исследование объявлений о продаже квартир

**Цель проекта** - исследование данных о квартирах, выставленных на продажу в Санкт-Петербурге и его пригородах, для получения информации о том, влияют ли на рыночную стоимость жилья различные факторы:
- площадь; 
- удаленность от центра города;
- высота потолков;
- количество комнат и др.

Массив данных содержит в себе информацию о параметрах объявлений о продаже квартир: цене, общей и жилой площади, количестве комнат, этажности дома и этаже квартиры, числе балконов, расстоянии до аэропорта или центра города, дате публикации объявления и др. 

В ходе исследования решается ряд **задач**:

- заполнение пропусков в столбцах; 
- изменение типа данных в столбцах;
- добавление новых столбцов в исходную таблицу с более наглядными для сравнения характеристиками;
- проведение анализа:
    + изучение основных параметров таблицы;
    + анализ времени продажи квартиры;
    + удаление выбросов;
    + изучение влияния на цену основных факторов;
    + определение населенных пунктов с самой высокой и низкой стоимостью жилья;
    + выделение центральной зоны с более дорогими квартирами;
    + анализ сегмента квартир в центральной зоне.

## Используемые инструменты
*pandas, matplotlib*
