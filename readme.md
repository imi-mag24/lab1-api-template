# Домашняя работа 1 Работа с API

Написать скрипт на Python для получения 100 случайных шуток из API https://api.chucknorris.io/ и сохранения их в БД SQLite.

При получении текста шуток нужно использовать асинхронную библиотеку [AIOHTTP](https://docs.aiohttp.org/en/stable/) и [асинхронные задания](https://docs.python.org/3/library/asyncio-task.html#creating-tasks).

После получения текстов нужно сохранить их в БД SQLite с помощью пакета [sqlite](https://docs.python.org/3/library/sqlite3.html) стандартной библиотеки.

В БД должны быть сохранены:
- `id` - идентификатор шутки
- `text` - текст шутки
- `url` — ссылка на шутку

Скрипт нужно сохранить в файле `main.py`.
