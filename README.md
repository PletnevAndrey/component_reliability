## Оценка влияния фактора загрязнения на надежность компонента

#### Исходные данные: 
Файл failures.xlsx в котором указана наработка на отказ (столбец Hours) компонента в часах. В некоторых случаях при исследовании причины отказа было выявлено загрязнение (столбец Factor). 

#### Задача: 
1. Определить, влияет ли загрязнение на надежность компонента (MTBF - mean time between failures). 
2. Определить закон распределения отказов.
3. Определить 95% доверительный интервал средней наработки на отказ.

## Выводы:

1. Сформирована гипотеза Н0: MTBF с загрязнением = MTBF без загрязнения и альтернативная Н1: MTBF не равны друг другу. Распределение средних наработки на отказ для двух групп подчиняются нормальному распределению, дисперсии гомогенные. Для проверки гипотезы использовался t-test, по результатам которого p-value = 0.188 > $\alpha$ 0.05. При этом мощность теста составила всего 25%. Соответственно можно говорить о недостаточности данных для вывода о какой то гипотезе с адекватной вероятностью ошибки.
2. Отказы компонента подчиняются нормальному закону распределения со средним 4597 л.ч. и стандартным отклонением 2599 л.ч.
3. 95% доверительный интервал для MTBF составляет (3798, 5397).
