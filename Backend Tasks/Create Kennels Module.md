---
assignee: Альберт Темирбулатов
task-id: B5
---
## **Описание задачи**

Инициализировать Модуль Kennels, описать базовые поля в схеме,  реализовать основные методы в сервисе, описать маршруты в контроллере и описать api документацию в bruno
Следующие необходимые функции:
1. Подача заявки на подтверждение кеннела (создание кеннела по сути). Не паблик.
2. Добавить функцию выхода пользователем из kennela.
3. Добавить функцию удаления kennela.
4. Получение информации о kennel по его Id.
5. Добавить функцию добавления новых пользователей в kennel.
6. Получение всех неподтвержденных кеннелов. Тут нужна валидация роли админа.
7. Подтверждение кеннела. Получает id кеннела в параметрах ссылки. Только для админов.
8. Для страницы кеннела нужно получение кеннела по id в параметрах ссылки. Тут нужна проверка админа кеннела: если не владелец или полностью админ сайта, ошибка.
9. Также нужна проверка при создании кеннела: если уже seller какого-то другого кеннела - ошибка

Заметки
Для метода invite нужно отменить добавление, если питомник не aprroved или не pending.
Если reject питомник, то нужна функция ChangeApplication(в которой меняется информация о питомнике и статус ставится на Pending), в начале функции проверяем, что только rejected, для disabled не будет работать.

---
## **Этапы выполнения**

| Ссылка на `commit`                                                                                   | Описание                                                                   |
| ---------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------- |
| [80c653b](https://github.com/iamfromhe1l/pet-market/commit/80c653b8454b970ef096d3d5dcb52a9579b14905) | Init Kennels module, create basic service, schema, controller and api docs |
| [39abe17](https://github.com/iamfromhe1l/pet-market/commit/39abe17224ac9d839bbeb4410baea721313fa985) | implemented kennelCreation and kennelLeave                                 |
| [568f8e4](https://github.com/iamfromhe1l/pet-market/commit/568f8e40521bb248e07c50d5d19c511a344d6b45) | Merge branch 'dev' into B5                                                 |
| [847f8de](https://github.com/iamfromhe1l/pet-market/commit/847f8de97500797533b4c033b23872a90d0c1096) | Auth fixes: added kennel to jwt and user return type                       |
| [bb46ec5](https://github.com/iamfromhe1l/pet-market/commit/bb46ec5c57387b896ddf9da3772a86f348352421) | Added more functions getKennelById, deleteKennel, leaveKennel              |
| [c1b7621](https://github.com/iamfromhe1l/pet-market/commit/c1b7621acffb4ca6552ddd97f68e129933306da3) | Implemented getUnapprovedKennels, inviteUser methods and routes            |

---
## **Комментарии**

