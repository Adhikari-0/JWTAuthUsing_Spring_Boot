<h3> The API must expose routes where some are accessible without authentication while others require one. Below are the routes: </h3><br/>

[POST] /auth/signup → Register a new user <br/>
[POST] /auth/login → Authenticate a user <br/>
[GET] /users/me → Retrieve the current authenticated user <br/>
[GET] /users → Retrieve the current authenticated user <br/>

The routes “/auth/signup” and “/auth/login” can be accessed without authentication while “users/me” and “users” require to be authenticated.
