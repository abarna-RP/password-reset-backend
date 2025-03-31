# register:api/auth/register
**post
{
    "username":"prabaabu",
"email":"prabaabu62@gmail.com",
"password":"abarna12@"
}
response registered successfully
# login : api/auth/login 
**post
{"email":"prabaabu62@gmail.com",
"password":"abarna12@"}
response login successfully
# forgotpassword: api/auth/forgot-password
**post
{"email":"prabaabu62@gmail.com"}
response: email sent
# resetpassword: api/auth/reset-password/token
**put
{
    "password":"abarna12#"
}
response: password reset successfully
![alt image](https://github.com/abarna-RP/password-reset-backend/blob/main/backend.png)
