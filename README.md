# todo-api

API 只接受JSON格式

## ``https://st-todo-api.herokuapp.com/``

## Routes

+ POST /todos  （创建一条新的todo）JSON应该包含   text = 'Test todo text’;

+ GET /todos  (返回当前帐号创建过的todo, 请求头部要包含 ``X-Auth`` 然后你是的token )

+ GET /todos/:id （ID 是todo的ID, 创建todo的时候API会返回）

+ DELETE /todos/:id  (删除匹配的todo)

+ PATCH /todos/:id  (更新匹配的todo, JSON要包含 ``completed`` 和 ``text``)

+ GET /users/me

+ POST /users   (创建用户，返回token) JSON应该包含``email``, ``password``

+ POST /users/login  (登录并返回token)

+ DELETE /users/me/token
