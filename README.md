UsersTemplate - скопировать и поменять на ServicesTemplate
В нем везде Users поменять на Services (если Users - Services, если User - Service, если user-service)

Так же у нем поменять таблицу (#, Логин, Роль) на #, Название услуги, Цена
Под этой таблицы идут переменные - iduser, login, role - поменять на id, name, price

В BaseTemplate нужно найти строчку  “Главная”, скопировать ее и поменять на Услуги, в href=“/services”

UserDBStorage скопировать, поменять на ServiceDBStorage, там так же  везде Users поменять на Services (если Users - Services, если User - Service, если user-service)
getAllUsers (должно быть getAllScores) - SELECT * FROM users поменять на services

Скопировать файл Users.php и поменять на Services.php, там так же  везде Users поменять на Services (если Users - Services, если User - Service, если user-service)
В getAll() поменять все Users на Services

В Router найти case “users”, скопировать и поменять все

БД

clients - id (int, A_I), name
services - id, name (varchar 100), price (int)
technic - id, name
services_item - id, client_id, technic_id, services_id, date (date)
