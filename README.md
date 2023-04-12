# CI и CD проекта api_yamdb
Задачей проекта yamdb_final является настройка для приложения "api_yamdb" Continuous Integration и Continuous Deployment, в результате реализован следующий функционал:
- Автоматический запуск тестов
- Обновление образов на Docker Hub
- Автоматический деплой на боевой сервер при пуше в главную ветку main

Адрес сервера:
```sh
http://51.250.109.198
```
Для проверки работоспособности используются следующие url:
```sh
http://51.250.109.198/redoc/
```
```sh
http://51.250.109.198/admin/
```
```sh
http://51.250.109.198/api/v1/
```

![Бейдж о статусе работы workflow](https://github.com/NikitaMikhailovich/yamdb_final/actions/workflows/yamdb_workflow.yml/badge.svg)

## License

MIT
