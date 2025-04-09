---
assignee: Akhmetov Kamil
task-id: B3
---
## **Описание задачи**

Implement JWT authentication, create guards, strategies, auth routes and DTOs. Add custom pipes/decorators (id, email, rt, public). Enable CORS, set /api prefix, apply global validation pipe. Document auth API in Bruno.

---
## **Этапы выполнения**

| Ссылка на `commit`                                                                                   | Описание                                                              |
| ---------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------- |
| [0d455f6](https://github.com/iamfromhe1l/pet-market/commit/0d455f67fb5cd106f5d709b9d8694d7dd0756299) | Created at and rt guards, strategies to jwt auth and public decorator |
| [c50b8ee](https://github.com/iamfromhe1l/pet-market/commit/c50b8ee400ae02dcabbf124007e001fb03af562c) | Implemented refreshRtHash() and AuthService methods                   |
| [9bdde2e](https://github.com/iamfromhe1l/pet-market/commit/9bdde2e7d12015912782d7521dc201bb5430bb17) | Created get_id,email,rt decorators and objectId parse pipe            |
| [0fea509](https://github.com/iamfromhe1l/pet-market/commit/0fea50981d605ea3fa4a6ddec895e5dc9188e94d) | Created dtos, auth routs and enabled atGuard in app.modul             |
| [e66d539](https://github.com/iamfromhe1l/pet-market/commit/e66d539a149244cf4f9549d0e02886d71b58eebf) | Enabled cors, /api prefix and global validation pipe in main.ts       |
| [25964d1](https://github.com/iamfromhe1l/pet-market/commit/25964d1d22db58dd0a1d9f4490d5aed7f22d3aa7) | Documented auth api routes in Bruno                                   |
| [f3b910e](https://github.com/iamfromhe1l/pet-market/commit/f3b910e20b8e1c0bfd1933cea90aef701de738ce) | B3 Squash commit                                                      |

---
## **Комментарии**

`пусто`