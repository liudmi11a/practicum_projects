# Анализ убытков приложения ProcrastinatePRO+

## Данные:
В нашем распоряжении три датасета. 
Файл:
- visits_info_short.csv хранит лог сервера с информацией о посещениях сайта, 
- orders_info_short.csv — информацию о заказах, 
- costs_info_short.csv — информацию о расходах на рекламу.

Структура visits_info_short.csv:
- User Id — уникальный идентификатор пользователя,
- Region — страна пользователя,
- Device — тип устройства пользователя,
- Channel — идентификатор источника перехода,
- Session Start — дата и время начала сессии,
- Session End — дата и время окончания сессии.

Структура orders_info_short.csv:
- User Id — уникальный идентификатор пользователя,
- Event Dt — дата и время покупки,
- Revenue — сумма заказа.

Структура costs_info_short.csv:
- dt — дата проведения рекламной кампании,
- Channel — идентификатор рекламного источника,
- costs — расходы на эту кампанию.

## Задача:
  
  Задача для маркетингового аналитика развлекательного приложения Procrastinate Pro+. Несмотря на огромные вложения в рекламу, последние несколько месяцев компания терпит убытки. Наша задача — разобраться в причинах и помочь компании выйти в плюс.

Есть данные о пользователях, привлечённых с 1 мая по 27 октября 2019 года:
- лог сервера с данными об их посещениях
- выгрузка их покупок за этот период
- рекламные расходы

## Описание проекта:

Провела анализ данных от ProcrastinatePRO+.
Рассчитала различные метрики, использовав когортный анализ: LTV, CAC, Retention rate, DAU, WAU, MAU и т.д. Используя уже написанные ранее функции расчёта метрик. Сделала правильные выводы по полученным данным.


## Общие выводы:
Из анализа данных приложения Procrastinate Pro+:

- Привлечение пользователей было в мае-октябре 2019 года из 'United States', 'UK', 'France', 'Germany'. Основная аудитория из США.
- Платящие пользователи чаще приходят из США и предпочитают мобильные устройства ('iPhone', 'Android').
- Самые эффективные рекламные источники: 'TipTop', 'organic'.
- Обнаружены излишние затраты на рекламу, особенно в США через 'TipTop' и 'AdNonSense'.
- Рекомендуется перераспределить бюджет в пользу более успешных каналов и сократить затраты на менее эффективные источники, особенно в США через 'TipTop'.

## Навыки и инструменты:
- Python
- Pandas
- Matplotlib
- когортный анализ
- юнит-экономика
- продуктовые метрики
- Seaborn

