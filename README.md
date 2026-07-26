# Владислав Тюрюмин

## Data Analyst / Product Analyst Intern

Студент МГТУ им. Н. Э. Баумана (ИУ9).

Интересуюсь аналитикой данных, продуктовой аналитикой и A/B-тестированием.

Работаю с SQL, Python, статистикой и BI-инструментами. Создаю проекты, связанные с анализом пользовательского поведения, продуктовых метрик, качеством данных и автоматизацией аналитических задач.

---

# Skills

## Programming & Data Analysis

- Python (pandas, NumPy, matplotlib, scipy, statsmodels)
- SQL (PostgreSQL)
- C++
- C
- Go (basic)

## Analytics

- Product Analytics
- A/B Testing
- Hypothesis Testing
- Funnel Analysis
- Cohort Analysis
- Retention Analysis
- Data Quality Analysis
- Exploratory Data Analysis

## Tools

- PostgreSQL
- Yandex DataLens
- Git / GitHub
- Jupyter Notebook


# Projects


## Marketplace Analytics Dashboard

🔗 https://github.com/wreaxtrr/marketplace-analytics-dashboard

**Stack:** PostgreSQL, SQL, Yandex DataLens

End-to-end BI проект для анализа ключевых показателей маркетплейса.

Проект включает подготовку аналитических данных, расчёт продуктовых метрик и создание интерактивных дашбордов.

### Что сделано:

- Подготовлены SQL-датасеты для анализа продаж, заказов, пользователей и продавцов.
- Реализована аналитика пользовательской воронки:
  `view → cart → purchase`.
- Рассчитаны основные продуктовые метрики:
  - DAU
  - Daily Active Customers
  - GMV
  - AOV
  - ARPU
  - ARPPU
  - Paid Orders Margin
- Проведён анализ seller cohorts и seller retention.
- Использованы CTE, JOIN, оконные функции и агрегатные запросы.
- Созданы интерактивные дашборды в Yandex DataLens для анализа динамики показателей.


---

# A/B Test Analysis — E-commerce Landing Page

🔗 https://github.com/wreaxtrr/ab-test-analysis-python

**Stack:** Python, pandas, NumPy, matplotlib, scipy, statsmodels, Jupyter Notebook

Проект по анализу результатов A/B-теста новой версии посадочной страницы e-commerce продукта.

Цель проекта — определить, улучшила ли новая версия страницы ключевые продуктовые метрики.

### Что сделано:

- Проведена подготовка и исследование данных эксперимента.
- Выполнен EDA:
  - анализ структуры данных;
  - проверка пропусков;
  - анализ распределений;
  - сравнение контрольной и тестовой групп.
- Рассчитаны продуктовые метрики:
  - Conversion Rate;
  - ARPU;
  - Average Check.
- Проведена проверка статистических гипотез.
- Использованы:
  - доверительные интервалы;
  - z-test для сравнения конверсий;
  - t-test для анализа числовых метрик.
- Интерпретированы результаты эксперимента с точки зрения продуктового решения.


---

# Food Delivery SQL Analytics

🔗 https://github.com/wreaxtrr/food-delivery-sql-analytics

**Stack:** PostgreSQL, SQL

Проектирование базы данных и аналитической модели для сервиса доставки еды.

Цель проекта — создать структуру данных, которая позволяет анализировать пользователей, рестораны, заказы, платежи и пользовательские события.

### Что сделано:

- Спроектирована логическая модель базы данных.
- Определены сущности:
  - users;
  - restaurants;
  - products;
  - orders;
  - payments;
  - promo codes;
  - couriers;
  - app events.
- Настроены связи между таблицами через первичные и внешние ключи.
- Подготовлены аналитические SQL-запросы.
- Реализована база для анализа:
  - заказов;
  - выручки;
  - пользовательской активности;
  - эффективности доставки.


---

# Retail Data Quality Analysis

🔗 https://github.com/wreaxtrr/retail-data-quality-analysis

**Stack:** Python, pandas, Jupyter Notebook

Проект по анализу качества данных перед проведением аналитических исследований.

Цель проекта — проверить исходный датасет и выявить проблемы, которые могут повлиять на результаты анализа.

### Что сделано:

- Проведена проверка качества данных.
- Выполнен анализ:
  - пропусков;
  - дубликатов;
  - некорректных значений;
  - выбросов.
- Исследована структура данных и основные статистические характеристики.
- Подготовлены рекомендации по очистке и дальнейшему использованию данных.
