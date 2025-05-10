<p align="center">
  <h1>🗄️ Структура базы данных</h1>
</p>

---

## Таблица `users`
| Поле | Тип | Описание |
|------|-----|----------|
| id | SERIAL | PK |
| telegram_id | BIGINT | ID в Telegram |
| full_name | VARCHAR(100) | ФИО |

## Таблица `tasks`
| Поле | Тип | Описание |
|------|-----|----------|
| id | SERIAL | PK |
| user_id | INT | FK к users |
| description | TEXT | Описание задачи |
| start_time | TIMESTAMP | Время начала |

---

<p align="center">
  <a href="commands.md">← Команды</a> | 
  <a href="README.md">На главную →</a>
</p>
