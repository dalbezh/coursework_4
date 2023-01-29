# Курсовая работа №4
___
#### Студент:
* **Баранов Александр**
___

### Архитектура приложения взята из 19-ой домашней работы. Из основного:
* Убраны ненужные представления
* Добавлены новые представления
* Добавлена пагинация
* Добавлен метод [валидации](app/services/auth.py)

### По выполненным критериям:
- [ ]  Бизнес логика находится в сервисах
- [ ]  Присутствует слой DAO вокруг моделей
- [ ]  В моделях присутствуют нужные поля
- [ ]  В схемах присутствуют нужные поля и не отдаются пароля
- [ ]  Отношения у моделей установлены
- [ ]  Отношения в сериализаторе сериализованы корректно
- [ ]  Коды ответов возвращаются согласно правилам REST 
___
### Frontend настраивал через docker контейнер.

___
### Задания со звёздочкой в разработке

* Описана документацию для swagger (эндпоинт /doc)
* Добавлены тесты для сервисов DirectorService, GenreService и MovieService