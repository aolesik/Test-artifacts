# Test-artifacts
Примеры тестовой документации 
## Чек-лист
- [Пример Чек-листа в Goggle Sheets](https://docs.google.com/spreadsheets/d/1JJQGbJL0nIcVcemTYnboXhoQi3G_GIfLmwKp-lqs7FQ/edit?usp=sharing)

## Тест-кейсы
- [Примеры тест-кейсов в Goggle Sheets](https://docs.google.com/spreadsheets/d/1dCS7DKHgZDOMgs68lynFhDm6U5dj5MN4LpmnOtX-7kw/edit?usp=sharing)

1. Авторизация через восстановление пароля по номеру телефона

    ![5](https://github.com/aolesik/Test-artifacts/assets/125824182/a164329e-8c55-4c79-b183-93e9c7baf79e)

2. Кол-во символов [0, 7]

    ![33](https://github.com/aolesik/Test-artifacts/assets/125824182/86a13be4-4dd8-418c-8f7d-3bdb59e33ae5)

3. Адаптивность верстки

    ![40](https://github.com/aolesik/Test-artifacts/assets/125824182/0de2c1bc-98ef-4cbf-8996-0ce9d56070fb)

4. Вставить ссылку
    
    ![28](https://github.com/aolesik/Test-artifacts/assets/125824182/3f862c8f-6f76-4d92-9824-c8a8c49f6ad1)
   
## Баг-репорты
- [Примеры Баг-репортов в Goggle Docs](https://docs.google.com/document/d/1Dgv5WmuxOD4z8S1W7gXs9yem7yGqmjkX8a_v2n1J-ks/edit?usp=sharing)

### Bug-Report №1:

| Title             | Description                                                                |
| ----------------- |----------------------------------------------------------------------------|
| `Header`          | [bug][web][prod]                                                           |
| `Description`     | Выпадающее меню не скрывается                                              |
| `Playback steps`  |   1. Открыть главную страницу  https://moscowzoo.ru/                       |
|                   |   2. Навести курсор на навигационное меню наверху страницы                 |
|                   |   3. Убрать курсор с выпадающего меню                                      |
|                   |                                                                            |
| `Current result`  | Выпадающее меню не скрывается                                              |
| `Expected Result` | Выпадающее меню скрывается. При прокрутке страницы также не скрывается     |
| `Environment`     | Windows 10 v 22H2, Chrome v 126.0.6478.127                                 |
| `Device`          | Inspiron 7720                                                              |
| `Analytics`       | Статистика сколько пользователей задела проблема                           |
| `Documentation`   | Ссылка на документацию                                                     |
| `Logs`            | Выборка из логов в момент получения бага                                   |
| `Slack`           | Ссылка на обсуждение этого бага                                            |
| `Severity`        | Minor                                                                      |
| `Priority`        | Low                                                                        |
| `Observers`       | Менеджеры Managers                                                         |
| `Executor`        | Разработчик Developer                                                      |

### Bug-Report №2:

| Title             | Description                                                                |
| ----------------- |----------------------------------------------------------------------------|
| `Header`          | [bug][web][prod]                                                           |
| `Description`     | Повторный показ уведомления об использовании Cookie                        |
| `Playback steps`  |   1. Открыть главную страницу https://www.planetarium-moscow.ru/           |
|                   |   2. Внизу страницы в  уведомлении об использовании Cookie нажать “ок”     |
|                   |   3. Перейти на другую страницу сайта                                      |
|                   |                                                                            |
| `Current result`  | Уведомление об использовании Cookie больше не появляется                   |
| `Expected Result` | Уведомление об использовании Cookie снова появляется при каждом переходе   |
|                   | на новую страницу сайта                                                    |
| `Environment`     | Windows 10 v 22H2, Chrome v 126.0.6478.127                                 |
| `Device`          | Inspiron 7720                                                              |
| `Analytics`       | Статистика сколько пользователей задела проблема                           |
| `Documentation`   | Ссылка на документацию                                                     |
| `Logs`            | Выборка из логов в момент получения бага                                   |
| `Slack`           | Ссылка на обсуждение этого бага                                            |
| `Severity`        | Minor                                                                      |
| `Priority`        | Low                                                                        |
| `Observers`       | Менеджеры Managers                                                         |
| `Executor`        | Разработчик Developer                                                      |
