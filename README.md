# Лабораторная работа №35: MemeBoard (Fullstack)

## 1. Выполнил работу

- **ФИО:** Dragonyafa  
- **Группа:** ИСП-233

## 2. Инструкция по запуску

### Бэкенд 

1. Откройте терминал и перейдите в папку с проектом API:
   ```bash
   cd MemesApi
2. Запустите сервер:
    ```bash
    dotnet run
### Запуск фронтенда
1. Откройте папку frontend в VS Code 

2. Откройте файл index.html.

3. Запустите Live Server (например, через расширение Live Server в VS Code).


### Таблица — что изучили

| Концепция | Где используется |
|-----------|------------------|
| `fetch(url)` | GET-запрос к API |
| `fetch(url, { method, headers, body })` | POST и DELETE запросы |
| `response.ok` | Проверка успешности ответа |
| `response.json()` | Чтение JSON из ответа |
| `JSON.stringify(...)` | Объект JS → JSON-строка для отправки |
| `async / await` | Ожидание ответа от сервера |
| `try / catch / finally` | Обработка ошибок при fetch |
| CORS | Разрешение запросов между разными портами |
| `AddCors` + `UseCors` | Включение CORS в ASP.NET Core — два шага |