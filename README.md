curl --location 'http://localhost:8080/auth/login' \
--header 'Content-Type: application/json' \
--data-raw '{
    "email" : "admin@gmail.com",
    "password" : "secret"
}'
