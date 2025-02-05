# Тема 8. Домашня робота

**Мета цього домашнього завдання** — створити REST API для зберігання та
управління контактами. API повинен бути побудований з використанням
інфраструктури FastAPI та повинен використовувати SQLAlchemy для управління
базою даних.

## Технічний опис завдання

1. **Контакти**

Для зберігання контактів вашої системи необхідно організувати базу даних, яка
буде містити всю необхідну інформацію.

Ця інформація повинна включати:

- Ім'я
- Прізвище
- Електронна адреса
- Номер телефону
- День народження
- Додаткові дані (необов'язково)

2. **API**

API, яке ви розробляєте, повинно підтримувати базові операції з даними. Нижче
наведено список дій, які ваш API повинен мати можливість виконувати::

- Створити новий контакт
- Отримати список всіх контактів
- Отримати один контакт за ідентифікатором
- Оновити контакт, що існує
- Видалити контакт

3. **CRUD API**

На придачу до базового функціоналу CRUD API також повинен мати наступні функції:

- Контакти повинні бути доступні для пошуку за іменем, прізвищем чи адресою
  електронної пошти (Query параметри).
- API повинен мати змогу отримати список контактів з днями народження на
  найближчі 7 днів.

## Загальні вимоги до виконання домашнього завдання

1. Використання фреймворку FastAPI для створення API
2. Використання ORM SQLAlchemy для роботи з базою даних
3. В якості бази даних слід використовувати PostgreSQL.
4. Підтримка CRUD операцій для контактів
5. Підтримка зберігання дати народження контакту
6. Надання Swagger документації для REST API
7. Використання модуля перевірки валідності даних Pydantic

## Підготовка та завантаження домашнього завдання

1. Створіть публічний репозиторій `goit-pythonweb-hw-08`.
2. Виконайте завдання та відправте його у свій репозиторій.
3. Завантажте робочі файли на свій комп’ютер та прикріпіть їх у LMS у форматі
   `zip`. Назва архіву повинна бути у форматі **ДЗ8_ПІБ**.
4. Прикріпіть посилання на репозиторій `goit-pythonweb-hw-08` та відправте на
   перевірку.

## Формат оцінювання

- Залік / Незалік

## Формат здачі

- Прикріплені файли репозиторію у форматі `zip` з назвою **ДЗ8_ПІБ**.
- Посилання на репозиторій.

> [!IMPORTANT]
>
> ВАЖЛИВО
>
> Перегляньте Інструкцію щодо завантаження робочого файлу з репозиторію на
> Github

### Результати виконаного завдання:

![Results](./assets/01.png)
