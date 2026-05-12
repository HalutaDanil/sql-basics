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

| Exercise | Topic |\n|----------|-------|\n| ex00 | Simple SELECT with sorting |\n| ex01 | Filtering with WHERE |\n| ex02 | DISTINCT and unique values |\n| ex03 | LIMIT and OFFSET |\n| ex04 | BETWEEN, IN |\n| ex05 | LIKE and patterns |\n| ex06 | IS NULL |\n| ex07 | ORDER BY with multiple fields |\n| ex08 | Aggregate functions |\n| ex09 | GROUP BY + HAVING |

### 🚀 Quick Start

```sql\n-- Top 3 pizzerias by average check\nSELECT p.name, AVG(m.price) as avg_price\nFROM pizzeria p\nJOIN menu m ON p.id = m.pizzeria_id\nGROUP BY p.name\nHAVING AVG(m.price) > 800\nORDER BY avg_price DESC\nLIMIT 3;\n```

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

| Задача | Тема |\n|--------|------|\n| ex00 | Простой SELECT с сортировкой |\n| ex01 | Фильтрация с WHERE |\n| ex02 | DISTINCT и уникальные значения |\n| ex03 | LIMIT и OFFSET |\n| ex04 | BETWEEN, IN |\n| ex05 | LIKE и паттерны |\n| ex06 | IS NULL |\n| ex07 | ORDER BY с несколькими полями |\n| ex08 | Агрегатные функции |\n| ex09 | GROUP BY + HAVING |

### 🚀 Быстрый старт

```sql\n-- Топ-3 пиццерии по среднему чеку\nSELECT p.name, AVG(m.price) as avg_price\nFROM pizzeria p\nJOIN menu m ON p.id = m.pizzeria_id\nGROUP BY p.name\nHAVING AVG(m.price) > 800\nORDER BY avg_price DESC\nLIMIT 3;\n```

---

<div align="center">

*Project from portfolio | Проект из портфолио*

</div>
