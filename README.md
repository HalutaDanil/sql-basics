<div align="center">

# SQL Basics

**[English](#english) | [Русский](#русский)**

</div>

---

<a name="english"></a>
## 🇬🇧 English

Introduction to SQL: from simple SELECT queries to complex table joins. Working with a dataset about pizzerias, people, and their visits.

### 🛠️ Tech Stack

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square)

### ✨ Features

| Exercise | Topic |
|----------|-------|
| ex00 | Simple SELECT with sorting |
| ex01 | Filtering with WHERE |
| ex02 | DISTINCT and unique values |
| ex03 | LIMIT and OFFSET |
| ex04 | BETWEEN, IN |
| ex05 | LIKE and patterns |
| ex06 | IS NULL |
| ex07 | ORDER BY with multiple fields |
| ex08 | Aggregate functions |
| ex09 | GROUP BY + HAVING |

### 🚀 Quick Start

```sql
-- Top 3 pizzerias by average check
SELECT p.name, AVG(m.price) as avg_price
FROM pizzeria p
JOIN menu m ON p.id = m.pizzeria_id
GROUP BY p.name
HAVING AVG(m.price) > 800
ORDER BY avg_price DESC
LIMIT 3;
```

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:58a6ff,50:1f6feb,100:0969da&height=2&section=header&text=&fontSize=1"/>
</div>

<a name="русский"></a>
## 🇷🇺 Русский

Введение в SQL: от простых SELECT-запросов до сложных объединений таблиц. Работа с датасетом о пиццериях, людях и их посещениях.

### 🛠️ Стек технологий

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square)

### ✨ Возможности

| Задача | Тема |
|--------|------|
| ex00 | Простой SELECT с сортировкой |
| ex01 | Фильтрация с WHERE |
| ex02 | DISTINCT и уникальные значения |
| ex03 | LIMIT и OFFSET |
| ex04 | BETWEEN, IN |
| ex05 | LIKE и паттерны |
| ex06 | IS NULL |
| ex07 | ORDER BY с несколькими полями |
| ex08 | Агрегатные функции |
| ex09 | GROUP BY + HAVING |

### 🚀 Быстрый старт

```sql
-- Топ-3 пиццерии по среднему чеку
SELECT p.name, AVG(m.price) as avg_price
FROM pizzeria p
JOIN menu m ON p.id = m.pizzeria_id
GROUP BY p.name
HAVING AVG(m.price) > 800
ORDER BY avg_price DESC
LIMIT 3;
```

---

<div align="center">

*Project from portfolio | Проект из портфолио*

</div>
