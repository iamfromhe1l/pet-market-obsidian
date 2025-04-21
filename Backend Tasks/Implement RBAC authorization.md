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

| Ссылка на `commit` | Описание                                                       |
| ------------------ | -------------------------------------------------------------- |
| []                 | Api docs and AtStrategy fixes                                  |
| [cff3450]          | Created rbacGuard, Role decorator and fixes                    |
| [db2a28c]          | Added _id to schema, getUser by jwt and eslint rules added     |
| [6297e92]          | jwtPayload fixes, trimed hashes from user returning and fixes  |
| [f0883d9]          | Implemented changeRole, set and remove admin role and api docs |
| []                 | B4 Squash commit                                               |

---
## **Комментарии**

`пусто`