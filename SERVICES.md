# Список микросервисов CashPilot

| Сервис               | Назначение | Репозиторий |
|----------------------|------------|-------------|
| **auth-service**     | Аутентификация и авторизация (JWT, OAuth2, роли) | [auth-service](https://github.com/Rus1IT/auth-service) |
| **profile-service**  | Данные пользователя, настройки, уведомления | [profile-service](https://github.com/Rus1IT/profile-service) |
| **account-service**  | Счета, кошельки, мультивалютность | [account-service](https://github.com/Rus1IT/account-service) |
| **transaction-service** | CRUD транзакций, обработка выписок | [transaction-service](https://github.com/Rus1IT/transaction-service) |
| **planning-service** | Категории, бюджеты, цели, лимиты | [planning-service](https://github.com/Rus1IT/planning-service) |
| **report-service**   | Отчёты, графики, аналитика | [report-service](https://github.com/Rus1IT/report-service) |
| **notification-service** | Пуш- и email-уведомления | [notification-service](https://github.com/Rus1IT/notification-service) |
| **export-service**   | Импорт/экспорт CSV, XLSX, PDF | [export-service](https://github.com/Rus1IT/export-service) |

## Дополнительно
- **AI-помощник** — отдельный модуль, интегрированный с `transaction-service` и `report-service`.
- **Группы пользователей** — статистика по участникам, объединение данных.
