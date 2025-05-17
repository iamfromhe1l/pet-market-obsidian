---
assignee: Альберт Темирбулатов
task-id: B6
---
## **Описание задачи**

Инициализировать Модуль Pets, описать базовые поля в схеме,  реализовать основные методы в сервисе, описать маршруты в контроллере и описать api документацию в bruno
Следующие необходимые функции:
1) Добавление животного в конкретный питомник по kennelId. (createPet)
2) Получить список всех животных в конкретном питомнике. (getPetsByKennel)
3) Получить одно животное по его id (для просмотра карточки животного). (getPetById)
4) Обновить информацию о животном. updatePet
5) Удалить животное. (deletePet)
6) Реализовать поиск животных по текстовому запросу в названии и описании. (searchPets)
7) Добавить фильтрацию по полу, цене, приюту и категории. (searchPets с фильтрами)
8) Добавить пагинацию и возврат общего количества результатов. (searchPets с pagination)
9) Реализовать сортировку по цене и названию. (searchPets с сортировкой)
10) Добавить опциональный populate питомника. (populateKennel при необходимости)
11) Внедрить модуль категорий в модули питомников и питомцев 
12) Исправить ошибки и недочеты в авторизации по ролям
13) Написать документацию api в Bruno

---
## **Этапы выполнения**

| Ссылка на `commit`                                                                                   | Описание                                                                              |
| ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- |
| [9143dfd](https://github.com/iamfromhe1l/pet-market/commit/9143dfdaa508b21f4888af9cca782e2b54ca61cb) | set up module structure and implement base schema and pet dto                         |
| [c929eb0](https://github.com/iamfromhe1l/pet-market/commit/c929eb099fb98b2c13fe41af015c1224dcccd831) | implement full CRUD, search with filters, pagination and sorting                      |
| [42a75bb](https://github.com/iamfromhe1l/pet-market/commit/42a75bb9b331a737d9fcbd0d0aba9ad5646b7367) | Adapted Categories Module for Kennels and Pets Moduls, documented APIs and auth.fixes |
| [e1d9801](https://github.com/iamfromhe1l/pet-market/commit/e1d9801974e3f62b9465e4853a1dd4d358569309) | B6 Squash commit                                                                      |

---
## **Комментарии**

Не забыть обратно внедрить Категории, когда они будут готовы.