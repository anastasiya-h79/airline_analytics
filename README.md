# -Аналитика в авиакомпании

Мы помогаем российской авиакомпании F9 проанализировать предпочтения пользователей, покупающих билеты на разные направления.

Задачи проекта:

предобработать данные
выбрать топ-10 городов по количеству рейсов;
построить графики: модели самолетов и количество рейсов, города и количество рейсов, топ-10 городов и количество рейсов;
сделать выводы по каждому из графиков, пояснить результат.
Стэк

Pandas, Plotly, Matplotlib

Данные

В нашем распоряжении 2 таблицы

/datasets/query_1.csv

model — модели самолета
flights_amount — количество рейсов для каждой модели самолетов model в сентябре 2018 года
/datasets/query_3.csv

city — городах
average_flights — среднем количестве рейсов, прибывающих в город city за день в августе 2018 года
Результат

В ходе работы мы проанализировали предпочтения пользователей, покупающих билеты на разные направления.

Больше всего рейсов за месяц выполняют самолеты Cessna, Bombardier и Sukhoi
Больше всего рейсов в день принимают аэропорты Москвы
Подавляющее большинство российских городов принимает всего лишь от 1 до 4 рейсов в день
