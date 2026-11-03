# Highload High-Availability Systems / Высоконагруженные высокодоступные системы

Курс о проектировании распределённых систем с высокими требованиями к производительности и надёжности. Рассматривает перевод бизнес-задач в технические требования, расчёт пропускной способности, SLO/SLA и архитектурные компромиссы.

## Материалы курса

- [Лекции: архитектура, нагрузка и надёжность](Lectures/README.md).
- [Пять лабораторных примеров 2025 года](Labs/README.md).

## Что изучают

- Docker и основы highload/high availability.
- Балансировку и горизонтальное масштабирование.
- Проектирование сокращателя URL и счётчика лайков.
- Kafka, асинхронность и событийные пайплайны.
- Системы уведомлений и обработку clickstream.
- Кэширование чтения и записи.
- Архитектуру социальной сети и системы рейтингов.
- OLTP, OLAP, работу с данными и шардирование.
- Проектирование мессенджера и рекомендательных сервисов.
- Надёжность, system design и обоснование архитектурных решений.

## Необходимые знания

Язык программирования высокого уровня, например Python, Go или Java; алгоритмы и структуры данных; клиент-серверное взаимодействие; основы ОС, сетей и реляционных БД.

## Формат

**3 з.е., 108 часов:** 24 часа лекций и 20 часов лабораторных. Смешанный формат, английский язык. Контроль — зачёт.

## Учебные материалы и проекты

[GennadiiFilatov/High-Load-Systems-Lab-2025](https://github.com/GennadiiFilatov/High-Load-Systems-Lab-2025) — пять лабораторных 2025 года. Автор поступил на Big Data and Machine Learning в 2024 году.

- [Лабораторная 1](https://github.com/GennadiiFilatov/High-Load-Systems-Lab-2025/tree/main/1st%20lab): Flask, Docker, k6, Prometheus/Grafana, нагрузка и оповещения.
- [Лабораторная 2](https://github.com/GennadiiFilatov/High-Load-Systems-Lab-2025/tree/main/2st_lab): варианты масштабирования, Nginx и нагрузочные тесты.
- [Лабораторная 3](https://github.com/GennadiiFilatov/High-Load-Systems-Lab-2025/blob/main/3rd_lab/app.py): Redis cache-aside, TTL, объединение параллельных запросов к одному ключу, PostgreSQL и метрики кэша.
- [Лабораторная 4](https://github.com/GennadiiFilatov/High-Load-Systems-Lab-2025/blob/main/4th_lab/docker-compose.yml): PostgreSQL master–replica, потоковая репликация и распределение чтений.
- [Лабораторная 5](https://github.com/GennadiiFilatov/High-Load-Systems-Lab-2025/blob/main/5th_lab/app.py): синхронный HTTP и Kafka producer/consumer, метрики запросов и сообщений.

## Ссылки

- [Страница дисциплины](https://my.itmo.ru/programs/59738).
