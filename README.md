# todo-api

API 只接受JSON格式

## Endpoint``https://st-todo-api.herokuapp.com/``

## Routes

+ POST /todos  （创建一条新的todo）JSON应该包含   text = 'Test todo text’;

+ GET /todos

+ GET /todos/:id （ID 是todo的ID, 创建todo的时候API会返回）

+ DELETE /todos/:id

+ PATCH /todos/:id

+ GET /users/me 

+ POST /users   (创建用户，返回token) JSON应该包含``email``, ``password``

+ POST /users/login

+ DELETE /users/me/token
