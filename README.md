
# Rails api for register login logout

## register

http://localhost:3000/signup

{
    "user": {
        "email": "a@a.a",
        "password": "aaaaaa"
    }
}

## login

http://localhost:3000/login

{
    "user": {
        "email": "a@a.a",
        "password": "aaaaaa"
    }
}

it returns authorization key in *header*

Authorization →Bearer eyJhbGciOiJIUzI1NiJ9.eyJzdWIiOiIxIiwic2NwIjoidXNlciIsImF1ZCI6bnVsbCwiaWF0IjoxNTY5NzQ1MjUzLCJleHAiOjE1Njk4MzE2NTMsImp0aSI6IjcwZjljYmM2LTJlZTUtNGIzMi1hMDhiLTk1NzU4M2JkNThlMSJ9.beSpKDx-2EXId_u2-OwYLw8sQ7Y_fPUrDl-QFPsxV8I

## logout

http://localhost:3000/logout

Authorization Bearer eyJhbGciOiJIUzI1NiJ9.eyJzdWIiOiIxIiwic2NwIjoidXNlciIsImF1ZCI6bnVsbCwiaWF0IjoxNTY5NzQ1MjUzLCJleHAiOjE1Njk4MzE2NTMsImp0aSI6IjcwZjljYmM2LTJlZTUtNGIzMi1hMDhiLTk1NzU4M2JkNThlMSJ9.beSpKDx-2EXId_u2-OwYLw8sQ7Y_fPUrDl-QFPsxV8I

add row in jwt_blacklists table

## Resources

https://medium.com/@mazik.wyry/rails-5-api-jwt-setup-in-minutes-using-devise-71670fd4ed03
