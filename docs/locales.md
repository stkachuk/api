# Локализация

В любом запросе к API можно указывать параметр `?locale=` для передачи значения локали (языка).
`GET /locales` возвращает список возможных значений (доступных локалей) в поле `id`.

```json
[
    {
        "id": "RU",
        "name": "Русский"
    },
    {
        "id": "EN",
        "name": "Английский"
    }
]
```

В справочнике возможны другие значения.

----

Пример: https://api.hh.ru/dictionaries?locale=EN
