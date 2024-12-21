# ACR & APM

Это пакетный менеджер для работы с пакетами `.apmkg`.

## Установка

1. Клонируйте репозиторий:
    ```
    git clone <repo-url>
    cd apmkg_manager
    ```

2. Установите зависимости:
    ```
    pip install -r requirements.txt
    ```

3. Для использования:
    ```
    python src/package_manager.py
    ```

## Структура пакетов

Пакеты с расширением `.apmkg` должны содержать:
- `manifest.json` — метаданные пакета.
- Основной код (например, Python-файлы).
