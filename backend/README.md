### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```bash
git clone https://github.com/yandex-praktikum/kittygram_backend.git
```

```bash
cd kittygram_backend
```

Cоздать и активировать виртуальное окружение:

```bash
python3 -m venv env
```

* Если у вас Linux/macOS

  ```bash
  source env/bin/activate
  ```
* Если у вас windows

  ```bash
  source env/scripts/activate
  ```

```bash
python3 -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```bash
pip install -r requirements.txt
```

Выполнить миграции:

```bash
python3 manage.py migrate
```

Запустить проект:

```bash
python3 manage.py runserver
```
