# Анализ конверсий по группам A и B

## Описание
Этот проект анализирует конверсии в двух группах, A и B, на основе данных о том, сколько пользователей из каждой группы выбрали вариант "Yes" или "No". В проекте использовался файл данных, содержащий информацию о пользователях, их группе (A или B) и их ответах на вопрос (Yes/No).

## Описание кода
1. **Фильтрация данных по группам A и B**: Данные фильтруются по значениям столбца `Group`, чтобы выделить пользователей, относящихся к группе A и группе B.
2. **Подсчет конверсий "Yes" и "No"**: Для каждой группы подсчитывается количество пользователей, которые выбрали "Yes" и "No" в столбце `Conversion`.
3. **Создание таблицы для визуализации**: Данные о конверсиях собираются в DataFrame для удобства визуализации.
4. **Построение графика**: Создается столбчатая диаграмма, отображающая конверсии по группам A и B, с аннотациями, показывающими количество пользователей, выбравших "Yes" и "No".
5. **Расчет процента конверсий**: Для каждой группы рассчитывается процент пользователей, выбравших "Yes", относительно общего числа пользователей в группе.


## Результаты
График показывает конверсии "Yes" и "No" для двух групп (A и B), а также процент пользователей, выбравших "Yes" в каждой группе. На основе расчетов видно, что группа B имеет более высокую конверсию "Yes" по сравнению с группой A:

- В группе A: 5.4% пользователей выбрали "Yes".
- В группе B: 14.1% пользователей выбрали "Yes".

## Требования
- Python 3.x
- Библиотеки: `pandas`, `matplotlib`

