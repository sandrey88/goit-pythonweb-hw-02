# ДЗ Тема: Основи технології Docker

## Способи запуску проєкту

### 1. Запуск через Docker (рекомендований спосіб)

Цей спосіб не потребує встановлення Python та PostgreSQL локально.

#### Вимоги:

- Встановлений Docker Desktop

#### Кроки запуску:

```bash
# Клонуйте репозиторій
git clone https://github.com/sandrey88/goit-pythonweb-hw-02.git
cd goit-pythonweb-hw-02

# Запустіть контейнери
docker-compose up
```

Після запуску, застосунок буде доступний за адресою: http://localhost:8000

### 2. Локальний запуск

#### Вимоги:

- Python 3.10
- PostgreSQL

#### Кроки запуску:

1. Створіть віртуальне оточення та встановіть залежності:

```bash
pip install -r requirements.txt
```

2. Змініть `db` на `localhost` в рядку підключення в db.py

3. Запустіть застосунок:

```bash
python main.py
```

Після запуску, застосунок буде доступний за адресою: http://localhost:3000
