# Лабораторная работа 1: VS Code + GitHub workflow

## Цель
Развернуть Python-проект в VS Code, настроить окружение, Git workflow и базовые проверки качества.

## Структура проекта
- `src/` — исходный код
- `tests/` — тесты
- `docs/` — документация процесса

## Создание и активация виртуального окружения
Linux/macOS:
```bash
python3 -m venv .venv
source .venv/bin/activate
```

Windows:
```bash
py -m venv .venv
.venv\Scripts\activate
```

## Установка зависимостей
```bash
pip install -r requirements.txt
```

## Запуск проекта
```bash
python src/app.py
```

## Локальные проверки
```bash
ruff check .
pytest
```

## Правила веток и коммитов
Подробные правила описаны в `docs/workflow.md`.
