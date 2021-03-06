# Collection and storage of data
**Analytics in the airline: data parsing, working with databases using Python and SQL**

**Цель проекта**: понять предпочтения пользователей, покупающих билеты на разные направления.

**Задача проекта**: изучить базу данных и проанализировать спрос пассажиров на рейсы в города, где проходят крупнейшие фестивали.

**Используемые инструменты и библиотеки**: SQL, requests, pandas, matplotlib

**Описание данных**:

Таблица airports — информация об аэропортах:

airport_code — трёхбуквенный код аэропорта,

airport_name — название аэропорта,

city — город,

timezone — часовой пояс.

Таблица aircrafts — информация о самолётах:

aircraft_code — код модели самолёта,

model — модель самолёта,

range — дальность полётов.

Таблица ticket — информация о билетах:

ticket_no — уникальный номер билета,

passenger_id — уникальный идентификатор пассажира,

passenger_name — имя и фамилия пассажира.

Таблица flights — информация о рейсах:

flight_id — уникальный идентификатор рейса,

departure_airport — аэропорт вылета,

departure_time — дата и время вылета,

arrival_airport — аэропорт прилёта,

arrival_time — дата и время прилёта,

aircraft_code — уникальный идентификатор самолёта.

Таблица ticket_flights — стыковая таблица «рейсы-билеты»:

ticket_no — номер билета,

flight_id — уникальный идентификатор рейса.

Таблица festivals — информация о фестивалях:

festival_id — уникальный номер фестиваля,

festival_date — дата проведения фестиваля,

festival_city — город проведения фестиваля,

festival_name — название фестиваля.

**Данные предоставлены:** Practicum by Yandex
