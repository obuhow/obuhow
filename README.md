- Привет, я Павел Обухов
- Практикую QA & Java & AI-agents
- Novosibirsk · [Telegram](https://t.me/obuhow) · [Email](mailto:p@obuhov.pro)

---

## Сейчас

Два года тестировал высоконагруженные сервисы массовых зачислений в **Сбере** — там я полюбил Java-стек (Spring, REST API, PostgreSQL, Kafka) и начал писать автотесты. После увольнения в **ноябре 2025** взял курс на backend-разработку:

- Углубился в **Java 17/21**, **Spring Boot 3.x**, **Spring Security**, REST API
- Прокачал работу с **PostgreSQL**, JPA/Hibernate
- Поднял **Docker + GitHub Actions** для автодеплоя собственных проектов

Веду самостоятельную релизную разработку учебных и коммерческих проектов.


---

## Главные проекты

### [TicTacToeWebGame](https://github.com/obuhow/TicTacToeWebGame) — учебный проект на Spring Boot

- Полноценный backend-проект для портфолио Java-разработчика: REST API, БД, авторизация, CI/CD, документация.

**Пишу весь код самостоятельно, использую LLM только для ревью и помощи в документировании.**

**Ссылки:**
- 🚀 Live demo: [http://195.19.20.116](http://195.19.20.116) 
- Swagger UI: [http://195.19.20.116:8081/swagger-ui/index.html](http://195.19.20.116:8081/swagger-ui/index.html)
- Текущий релиз: **1.0** · следующий: **1.1**

<details>
<summary><b>Подробнее</b></summary>

**Что внутри:**
- **Одиночный режим** — игрок против компьютера (алгоритм **минимакс**)
- **Многопользовательский режим** — два игрока по очереди
- **Регистрация и аутентификация** — Spring Security, Basic Auth, кастомный фильтр
- **PostgreSQL** через Spring Data JPA (Hibernate)
- **Swagger UI** — интерактивная документация API
- **Docker** + **GitHub Actions** — CI/CD с автодеплоем на Cloud.ru
</details>

**Стек:** `Java 21` · `Spring Boot 3.1.5` · `Gradle 8.5` · `Vue 3 (Vite)` · `PostgreSQL 14` · `Springdoc OpenAPI` · `Docker` · `GHCR` · `GitHub Actions` · `Cloud.ru`



---

### [WolfsOwnLifeFramework](https://github.com/obuhow/WolfsOwnLifeFramework) — Open-source проект на клиент-серверной архитектуре. Код пишет LLM, я пишу требования, организую workflow, управляю агентской разработкой.

- Система управления свободным временем для предпринимателей, фрилансеров, художников, разработчиков

**Мои правила агентской разработки:**
- Разрабатываю по SDD (Spec-Driven Development) с применением скиллов grill-me, to-spec, to-tickets, implement, review
- Для разработки арендую отдельный VPS, на который устанавливаю LLM-агентов для разработки. Это важно, чтобы на производительность процесса кодинга не влияли другие запущенные на машине приложения (как если это было бы на локальной машине разработчика)
- Разрабатываю на тех языках и с применением тех фреймворков, которые знаю, и на которых есть самостоятельный опыт - Java, JavaScript, bash
- Размещаю ПО на своих серверах везде, где возможно, для минимизации зависимостей от внешних поставщиков услуг. Так вместо использования n8n, парсеров, ai-агентов по подписке, устанавливаю все эти приложения на своих серверах
- Использую доступные бесплатно LLM (Nemotron Ultra, Gemini Flash, Hy3) для работы над приложением. Платные более мощные LLM подключаю, если бесплатная сеть не справляется, а также для ревью и рефакторинга (GPT 5.6 Luna - лидер по отношению цена/качество при оплате за трафик, Claude Opus - лидер цена/качество по подписке)


**Стек:** `Java 21` · `Spring Boot 3` · `Gradle` · `Vue 3 (Vite)` · `PostgreSQL 16` · `Docker`.


<!---
obuhow/obuhow is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

