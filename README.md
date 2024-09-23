<h2> Backend </h2>

<h3> The API must expose routes where some are accessible without authentication while others require one. Below are the routes: </h3><br/>
All the routes are present in the controllers Package, you can view all of them. <br>

[POST] /auth/signup → Register a new user <br/>
[POST] /auth/login → Authenticate a user <br/>
[GET] /users/me → Retrieve the current authenticated user <br/>
[GET] /users → Retrieve the current authenticated user <br/>

The routes “/auth/signup” and “/auth/login” can be accessed without authentication while “users/me” and “users” require to be authenticated.

<h4> There is more logic added in the program for the latest update of Role Base Access Control, you can ignore them. </h4>

# You can expand the application without doing much more things
