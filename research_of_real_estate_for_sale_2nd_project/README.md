# Проект "Исследование объявлений о продаже квартир"


## Цель
Исследовать данные из объявлений о продаже квартир, выявить важные характеристики, влияющие на стоиомсть квартиры.  

## Вывод
**Анализ времени продаж:**<br>
Большая часть квартир продаётся в в период до 70 дней.<br>
Быстрая продажа - до 45 дней.<br>

**Аномальные значения:**<br>
Преобладающее кол-во объявления находилось в ценовой зоне до 20 млн. Однако часто встречаются предложения около 30 млн. Выше - редкость.<br>
Квартиры с 6 и более комнатами - редкость.<br>
Высота потолков более чем 3 м. встречается очень редко.<br>
Площадь квартиры выше 100 кв м встречается редко.<br>

**Какие факторы больше всего влияют на стоимость квартиры?**<br>
Стоимость квадратного метра достаточно сильно влияет на цену объекта.<br>
Самая дорогая цена кв. м. в Санкт-Петербурге.<br>
Самая низкая в Выборге.<br>

**Факторы, влияющие на цену квартир в центре:**<br>
Площадь.<br>
Количество комнат.<br>
Выяснилось, что количество комнат негативно влияет на стоимость квадратного метра квартир в центре. Вероятно, так характеризуются бывшие коммунальные квартиры.<br>
Количество этажей.<br>

**Сравнение квартир в центре СПб и за его пределами:**<br>
Количество комнат за пределами центра больше влияет на стоимость квартиры, чем в центре.<br>
Удалённость квартир в центре от центра не так сильно влияет на стоимость, в отличие от квартир за его пределами.<br>
Количество этажей в центре больше влияет на стоимость квартиры, в отличие от недвижимости за пределами центра.<br>
Год, месяц или день недели размещения объявления не влияет на цену.<br>

**Исследование по центру:**<br>
Цена квадратного метра снижается в периоде удалённость от центра 0-3 км. Затем цена начинает расти в периоде от 3 км. до 6 км. Затем снова начинает падать и имеет уже устойчивый тренд вниз.<br>
Дата размещения объявления (месяц, год, день недели) не влияет на цену квартиры.<br>
<br>
**Объекты недвижимости в центре обладают следующими характеристикам:**<br>
Малоэтажные здания. Как правило до 5 этажей. <br>
Распространённая высота потолков либо 2,6-2,7 м., либо 3 м.<br>
Количество комнат зависит от площади.<br>

**Общий вывод:**<br>
По квартирам в центре:<br>
Центр Санкт-Петербурга - округ, радиус которого равен 3 км. Стоимость квартир зависит от площади, количества комнат. Для центра количество комнат негативно влияет на цену квадратного метра, в отличие от квартир за его пределами. Также на стоимость квартиры в центре оказывает влияние количество этажей. Вероятно, в домах с этажность повыше можно встретить наличие лифта.

По всем квартирам:<br>
Настоящей удачей станет сделка на продажу квартиры в течение 45 дней с момента размещения объявления, хотя большая часть квартир реализуется в срок до 70 дней.  
  
## Используемые библиотеки
- Pandas
- Matplotlib
- math
