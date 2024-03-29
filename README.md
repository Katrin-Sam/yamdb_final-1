![yamdb_workflow](https://github.com/mamontovdn/yamdb_final/workflows/yamdb_workflow/badge.svg)

# *Описание проекта:* #
 Проект YaMDb собирает отзывы пользователей на произведения. Сами произведения в YaMDb не хранятся, здесь нельзя посмотреть фильм или послушать музыку. Произведения делятся на категории и жанры с возможностью поиска по определенным критериям. Пользователи могут оставлять к произведениям отзывы и ставить им оценку, таким образом, из пользовательских оценок формируется усреднённая оценка произведения — рейтинг.

| Технологии |
| ---------- |
| Python |
| Django |
| DRF |
| Docker |
| Nginx |
| Gunicorn |

Проект содержит в себе REST API.

Как запустить проект:
1. Клонировать репозиторий и перейти в каталог с файлом композиции:
```
git clone git@github.com:kitah-ru/infra_sp2.git | cd infra_sp2/infra/
```

2. Запустить docker-compose:
```
docker-compose up -d
```

3. Далее можно работать с проектом


Примеры запросов к API можно посмотреть по адресу /redoc/ после запуска проекта.
