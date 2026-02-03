# WeatherApp2

## Описание проекта

**WeatherApp2** — это приложение на Python для получения погодной информации. Основной скрипт проекта (`main.py`) реализует логику обработки данных о погоде (например, через стороннее API) и отображает результат пользователю. Проект включает статические ресурсы, модули и изображения для интерфейса и логики приложения.

---

## Содержание

- [Описание проекта](#описание-проекта)  
- [Содержание](#содержание)  
- [Установка и запуск](#установка-и-запуск)  
- [Структура проекта](#структура-проекта)

---

## Установка и запуск

### 1. Клонирование репозитория

```shell
git clone https://github.com/b5ysQoPl9xBhrYPt6/WeatherApp2.git
cd WeatherApp2
```

### 2. Создание виртуального окружения

```shell
python -m venv venv
```

Активация окружения:

* **Windows**:
    ```shell
    venv\Scripts\activate
    ```

* **macOS / Linux**:
    ```shell
    source venv/bin/activate
    ```

### 3. Установка зависимостей

```shell
pip install -r requirements.txt
```

### 4. Запуск проекта

```shell
python main.py
```

---

## Структура проекта

```
WeatherApp2/
├── images/
├── modules/
    ├── gui/
        ├── __init__.py
        ├── city_weather.py
        ├── forecast_component.py
        ├── forecast_frame.py
        ├── image.py
        ├── main_info.py
        ├── main_screen.py
        └── side_bar.py
    ├── __init__.py
    ├── read_json.py
    ├── weather_data.py
    └── write_json.py
├── static/
    ├── config.json
    ├── forecast.json
    └── weather_data.json
├── .gitignore
├── main.py
├── README.md
└── requirements.txt
```

**Описание ключевых файлов:**

- `main.py` — точка входа приложения.
- `modules/` — вспомогательные модули с бизнес-логикой.
- `static/` — статические ресурсы для фронтэнда или отображения.
- `images/` — графические ресурсы (иконки, фото и пр.).
- `requirements.txt` — библиотеки Python, требуемые для работы приложения.

