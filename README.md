<div align="center">

# SQL Basics

**[English](#english) | [Русский](#русский)**

</div>

---

<a name="english"></a>
## 🇬🇧 English

First steps into SQL using a pizzeria dataset. The goal was to learn how to ask precise questions of a relational database and get exactly the data needed.

### What was done

| Task | What & Why |
|------|-----------|
| Simple SELECT | Retrieved all rows from a table. The foundation of every query. |
| Filtering (WHERE) | Selected rows matching conditions. Learned how databases filter data at the engine level. |
| DISTINCT | Extracted unique values. Essential for deduplication and understanding data cardinality. |
| LIMIT / OFFSET | Paginated results. Critical for performance when dealing with large tables. |
| BETWEEN / IN | Checked ranges and membership sets. More readable and often faster than multiple OR conditions. |
| LIKE | Searched with wildcards. Learned pattern matching for partial string queries. |
| IS NULL | Found missing data. Real-world data is incomplete; knowing how to handle NULLs is crucial. |
| Multi-column ORDER BY | Sorted by multiple fields with different directions. Precision in result ordering. |
| Aggregates | Used `COUNT`, `SUM`, `AVG`, `MIN`, `MAX`. Transformed raw rows into summary statistics. |
| GROUP BY + HAVING | Grouped data and filtered groups. Learned the difference between `WHERE` (row filter) and `HAVING` (group filter). |

### Key takeaways
- SQL is declarative: you describe **what** you want, not **how** to get it.
- `WHERE` filters rows before aggregation; `HAVING` filters after. Mixing them up is a common beginner mistake.
- NULL is not a value — it is the absence of one. `IS NULL` is the only correct way to check for it.

### Tech Stack

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square)

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:58a6ff,50:1f6feb,100:0969da&height=2&section=header&text=&fontSize=1"/>
</div>

<a name="русский"></a>
## 🇷🇺 Русский

Первые шаги в SQL на датасете пиццерий. Цель — научиться задавать точные вопросы реляционной базе данных и получать именно нужные данные.

### Что было сделано

| Задача | Что и зачем |
|--------|-------------|
| Простой SELECT | Получение всех строк из таблицы. Основа любого запроса. |
| Фильтрация (WHERE) | Выбор строк по условиям. Изучено, как база данных фильтрует данные на уровне движка. |
| DISTINCT | Извлечение уникальных значений. Необходимо для дедупликации и понимания кардинальности данных. |
| LIMIT / OFFSET | Пагинация результатов. Критично для производительности при работе с большими таблицами. |
| BETWEEN / IN | Проверка диапазонов и множеств. Читабельнее и часто быстрее множественных OR. |
| LIKE | Поиск с подстановочными символами. Изучено паттерн-матчинг для частичных строковых запросов. |
| IS NULL | Поиск отсутствующих данных. Реальные данные неполны; умение работать с NULL критично. |
| ORDER BY по нескольким колонкам | Сортировка по нескольким полям с разными направлениями. Точность в упорядочивании результатов. |
| Агрегатные функции | Использование `COUNT`, `SUM`, `AVG`, `MIN`, `MAX`. Преобразование сырых строк в сводную статистику. |
| GROUP BY + HAVING | Группировка данных и фильтрация групп. Изучена разница между `WHERE` (фильтр строк) и `HAVING` (фильтр групп). |

### Ключевые выводы
- SQL декларативен: вы описываете, **что** хотите получить, а не **как** это сделать.
- `WHERE` фильтрует строки до агрегации; `HAVING` — после. Их путаница — типичная ошибка новичков.
- NULL — не значение, а его отсутствие. `IS NULL` — единственно верный способ проверки.

### Стек технологий

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square)

---

<div align="center">

*Project from portfolio | Проект из портфолио*

</div>
