# SQL Basics

> Основы работы с реляционными базами данных на PostgreSQL

## О проекте

Введение в SQL: от простых `SELECT`-запросов до сложных объединений таблиц. Работа с датасетом о пиццериях, людях и их посещениях.

## Что изучено

| Задача | Тема |
|--------|------|
| `ex00` | Простой `SELECT` с сортировкой |
| `ex01` | Фильтрация с `WHERE` |
| `ex02` | `DISTINCT` и уникальные значения |
| `ex03` | `LIMIT` и `OFFSET` |
| `ex04` | `BETWEEN`, `IN` |
| `ex05` | `LIKE` и паттерны |
| `ex06` | `IS NULL` |
| `ex07` | `ORDER BY` с несколькими полями |
| `ex08` | Агрегатные функции: `COUNT`, `SUM`, `AVG` |
| `ex09` | `GROUP BY` + `HAVING` |

## Пример запроса

```sql
-- Найти топ-3 пиццерии по среднему чеку
SELECT p.name, AVG(m.price) as avg_price
FROM pizzeria p
JOIN menu m ON p.id = m.pizzeria_id
GROUP BY p.name
HAVING AVG(m.price) > 800
ORDER BY avg_price DESC
LIMIT 3;
```

## Технологии

- **PostgreSQL** — реляционная СУБД
- **Чистый SQL** — без ORM и фреймворков

---

*Решено в рамках обучения работе с базами данных*
