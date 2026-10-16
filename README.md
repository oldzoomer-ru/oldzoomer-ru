# Егор Гаврилов

Java-разработчик · Кстово, Россия

[Сайт](https://oldzoomer.ru/) · [GitHub](https://github.com/oldzoomer) · [LinkedIn](https://www.linkedin.com/in/oldzoomer/) · [work@oldzoomer.ru](mailto:work@oldzoomer.ru)

## Обо мне

Java-разработчик с коммерческим опытом переноса legacy-систем с Microsoft Access на Java / Spring Boot и разработки интерфейсов на Vaadin.

В личных проектах работаю с PostgreSQL, Kafka, Redis и Docker. Участвую в open source.

## Опыт работы

### AISA IT-Service — Junior Java Developer

Апрель — август 2024, Санкт-Петербург

Участвовал в переносе системы планирования бюджета Санкт-Петербурга с Microsoft Access на Java.

- Перенёс бизнес-логику на Java 17 / Spring Boot.
- Разработал веб-интерфейсы на Vaadin 23 взамен форм Microsoft Access / VBA.
- Настроил взаимодействие с хранимыми процедурами Microsoft SQL Server.
- Исправил ошибки бизнес-логики и разработал более 20 аналитических и отчётных модулей.

## Личные проекты

### StingrayTV Alice

Интеграция платформы StingrayTV с голосовым помощником Алисой.

- Разработал прототип, получивший положительную обратную связь от GS Labs.
- Защитил API с помощью Spring Security OAuth2 Resource Server и Keycloak.
- Вынес mDNS в отдельный контейнер, исключив необходимость доступа основного приложения к host network.
- Настроил Docker Compose и CI в GitHub Actions. Уменьшил размер контейнерного образа в 2 раза.

### NodehistJ

Система сбора и анализа исторических данных FidoNet на Java 25, Spring Data JDBC и PostgreSQL.

- Сократил время индексации с 3 дней до 30 минут, заменив LIMIT/OFFSET на потоковое чтение.
- Добавил кэширование в Redis и доставку данных через Kafka и S3.
- Уменьшил размер контейнерного образа в 5 раз с помощью GraalVM Native Image и Distroless.
- Настроил Docker Compose и CI в GitHub Actions.

## Навыки

- **Java:** Java 17/25, Spring Boot, Spring Data JDBC, Spring Security, Vaadin.
- **Данные:** PostgreSQL, Microsoft SQL Server, Redis, Kafka, S3.
- **Инструменты:** Docker, Linux, Git, GitHub Actions, GraalVM, JUnit, Mockito.
- **Интеграции:** REST API, OAuth2, Keycloak.

## Open Source

- **NetBSD / pkgsrc:** реализовал обход проблемы Year 2038 в libuuid. Изменения приняты в основную ветку, PR pkg/59637.
- **FidoIP:** перенёс изменения из своего проекта FidoIP-NG в основной проект; они вошли в версию 2.0.4.
- **FidoNet:** администрирую узел 2:5015/519 с декабря 2024 года.

## Образование

**МВЕК, Ижевск**
Среднее профессиональное образование, «Информационные системы и программирование».
Сентябрь 2021 — февраль 2026.

## Сертификаты

- [Certified Vaadin 24 Developer](https://vaadin.com/learn/certificate/d95d845a-c586-479d-916b-e08d536462fc) — февраль 2026.
- [Certified Vaadin 14 Developer](http://vaadin.com/learn/certificate/c8b81823-d458-4e5b-bb3e-72d4b25831fe) — июль 2026.
- [Cloud.ru Cloud Fundamentals](https://awardme.ru/ru/badges/8168a9f4-2513-456c-92c3-7c72ee6cdfdd) — март 2026.
- [Cloud.ru Evolution Fundamentals](https://awardme.ru/ru/badges/93602b2c-b7c4-4da3-b4cc-e0d335d04b73) — март 2026.
