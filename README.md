# Исследование объявлений о продаже квартир

### Опсиание проекта 
На основе данных сервиса Яндекс.Недвижимость определена рыночная стоимость объектов недвижимости разного типа, типичные параметры квартир, в зависимости от
удаленности от центра. Проведена предобработка данных. Добавлены новые данные. Построены гистограммы, боксплоты, диаграммы рассеивания.

### Задача: 
Используя данные сервиса Яндекс.Недвижимость, определить рыночную стоимость объектов недвижимости и типичные параметры квартир.

### Инструменты: 
Python, Pandas, Matplotlib, исследовательский анализ данных, предобработка данных, визуализация данных

### Ключевые слова: 
обработка данных, histogram, boxplot, scattermatrix, категоризация, scatterplot, фрод-мониторинг

### Выводы
На первом этапе мы выявили и заполнили пропуски. Удалили дубликаты в данных. А также добавили новые параметры для исследования:(цена одного квадратного метра; день публикации объявления, месяц публикации объявления, год публикации объявления, тип этажа квартиры,расстояние до центра города в километрах).

На втором этапе оценили какие параметры вляют на стоимость квартиры и пришли к следующим выводам:
1) Чем больше общая и жилая площадь, тем больше стоимость квартир.
2) Стоимость квартир растет с увеличением комнат.
3) На первом и последнем этаже квартиры значительно дешевле, чем на остальных.
4) С увеличением высоты потолков незначительно растет стоимость квартир, при этом самые дорогие квартиры с высотой 3.85 метра.
5) Начиная с 2014 и до 2018 года стоимость квартир падала, в 2019 году произошел небольшой рост.
6) Самые дорогие продажи с объявлением, размещенным в июне, а самыми недорогими - в октябре.
7) Cреди 10 населенных пунктов с наибольшим числом объявлений самый дорогой квадртаный метр в Санкт-Петербурге, а самый дешевый в Выборге.
8) C удаленностью от центра Санкт-Петербугра уменьшается и стоимость квартиры.


