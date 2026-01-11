# Обо мне

Java Backend-разработчик. Работаю с Java 17/21/25, Spring Boot 3.x/4.x.

## Ключевые проекты

NodehistJ — архивация и анализ 40-летней истории Фидонета  
GitHub: <https://github.com/oldzoomer-ru/nodehistj> 
- Решил задачу долгосрочного хранения и сравнения nodelist’ов с 1984 года (до 40 000 узлов в файле).  
- Архитектура: MinIO, Kafka (Redpanda), Redis, PostgreSQL, Spring Boot, Docker.

StingrayTV Alice — IoT-шлюз для управления ресивером Триколора через Алису  
GitHub: <https://github.com/oldzoomer-ru/stingraytv-alice>
- Построил шлюз, который связывает ресивер в локальной сети с Алисой.  
- Реализована полная интеграция с API Яндекс Умного дома (REST API, OAuth2, JWT).  
- Stateless-архитектура: состояние хранится только на ресивере, само приложение не хранит данных о состоянии.  
- Безопасность: Keycloak + Spring Security OAuth2 Resource Server.

Все проекты сопровождаются CI/CD (GitHub Actions), покрыты автотестами (JUnit Jupiter, Mockito), собираются в минимальные Docker-образы.

## Контакты

Email: <work@oldzoomer.ru>

Telegram: <https://t.me/oldzoomer_ru>

Хабр: <https://habr.com/ru/users/oldzoomer/>

[Поддержать меня](SPONSORSHIP.md)

## Насчёт FidoNet

Я являюсь одним из самых молодых участников данной legacy-сети в настоящее время, с нодовым адресом [2:5015/519](https://nodehist.wfido.ru/index.cgi?address=2%3A5015%2F519).

Если вы хотите получить поинтовый адрес, [обратитесь ко мне](mailto:fidonet@oldzoomer.ru).
