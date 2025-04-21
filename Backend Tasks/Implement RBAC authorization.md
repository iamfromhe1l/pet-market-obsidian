---
assignee: Akhmetov Kamil
task-id: B4
---
## **Описание задачи**

Implement RBAC authorization method, Roles decorator, add role into jwt payload. add methods to change roles.
Implement helper functions such as ObjectIdPipe, jwt payload extracters to id, email, role
Hot fixes of B3 branch 

---
## **Этапы выполнения**

| Ссылка на `commit`                                                                                   | Описание                                                       |
| ---------------------------------------------------------------------------------------------------- | -------------------------------------------------------------- |
| [84076e8](https://github.com/iamfromhe1l/pet-market/commit/84076e8e5dc9bdc6d22f7b69017c27b658212df9) | Api docs and AtStrategy fixes                                  |
| [cff3450](https://github.com/iamfromhe1l/pet-market/commit/cff34509abde015497cef6bf3e38a5c0093c1bb9) | Created rbacGuard, Role decorator and fixes                    |
| [db2a28c](https://github.com/iamfromhe1l/pet-market/commit/db2a28cf5c1239df0cabdeb25c4c4f9038ee7e80) | Added _id to schema, getUser by jwt and eslint rules added     |
| [6297e92](https://github.com/iamfromhe1l/pet-market/commit/6297e920a7f125acd67efe539ee0d3b21c01218d) | jwtPayload fixes, trimed hashes from user returning and fixes  |
| [f0883d9](https://github.com/iamfromhe1l/pet-market/commit/f0883d9d23ab96062c194fc89772bc5a080019fe) | Implemented changeRole, set and remove admin role and api docs |
| [8ab6049](https://github.com/iamfromhe1l/pet-market/commit/8ab60497847d780f3567b4ee894adb4e23780b4c) | B4 Squash commit                                               |

---
## **Комментарии**

`пусто`