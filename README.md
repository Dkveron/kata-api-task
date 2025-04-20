# kata-api-task

1. Зарегистрировался через эндпоинт:
POST https://blog-platform.kata.academy/api/users

с телом запроса в формате JSON:
```json
{
  "user": {
    "username": "Dk",
    "email": "yyy@yandex.ru",
    "password": "12345678"
  }
}

2.	Залогинился через эндпоинт:

POST https://blog-platform.kata.academy/api/users/login
в ответе получил токен

3.	Получил данные текущего пользователя через эндпоинт:
GET https://blog-platform.kata.academy/api/user

Использовал заголовок авторизации:
Authorization: Token eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY4MDRhZjRjYzVjZDM2MWIwMDkxMGEyOCIsInVzZXJuYW1lIjoiZGsiLCJleHAiOjE3NTAzMjE0ODUsImlhdCI6MTc0NTEzNzQ4NX0.TMLrB_a_pcuuyHZeCD__0cA2TITIdR1SFjpgtOCBcPY


