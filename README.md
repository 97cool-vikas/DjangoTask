# DjangoTask
A Rest Api with postgresql as database.

Here i can able to achive these :

1.User Sign Up (http://127.0.0.1:8000/api/profile/)
simlpy just put all the details in email,name,password and your profile gets created you can check by reloading (http://127.0.0.1:8000/api/profile/)

2.Uses JWT authentication
Jwt authentication is used , here modheader is used while authorization For loggin (http://127.0.0.1:8000/api/login/) put your email and password and you recive the token just pasted that token on modheader request header authorization and (http://127.0.0.1:8000/api/login/) + user id that is created while making new user you can also check by (http://127.0.0.1:8000/api/profile/) and simply using the filter Now you are inside your profile and you can delete your profile if you want

3.Must define 3 user levels : 1. Super-admin, 2. Teacher, 3. Student (Use internal Django Groups to achieve the same)
user levels can be achived by 1// Django admin 2// or 3// by simply using filter in (http://127.0.0.1:8000/api/profile/)

4.Teacher must be able to list all the students.

Using Filter

5.Admin must be able to list every user in the database.

By using django admin

6.Students must be able to see his information only.

Using Filter

7.Code should be commented for clarity.

Done
