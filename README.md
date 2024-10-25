# HW-Docker-in-practice

# Задача 0

docker-compose не установлен
![image](https://github.com/user-attachments/assets/c9279eaf-51fe-4ff8-899b-fc879db1194d)

docker compose версии, подходящей под условия, установлен
![image](https://github.com/user-attachments/assets/09e193bf-c366-4c7d-9004-94fe8a53c30f)

# Задача 1

Ссылка на форк репозитория https://github.com/g-timokhin/shvirtd-example-python/tree/main

# Задача 3

Запуск проекта

![image](https://github.com/user-attachments/assets/56c38993-b152-4a12-8212-a9052f243094)
![image](https://github.com/user-attachments/assets/128d53db-bf85-4cd8-8c5a-bd8a93457e9b)

Обращение к localhost

![image](https://github.com/user-attachments/assets/90dab6d2-90ac-4d01-abb7-9e76b38ebde9)

Подключение к БД

![image](https://github.com/user-attachments/assets/8caa0086-f404-4445-9b11-e4045926e18e)

Список баз

![image](https://github.com/user-attachments/assets/94ebad66-7ccb-4cfc-9f06-1dfffe18131b)

Просмотр данных в базе virtd

![image](https://github.com/user-attachments/assets/4f79861d-a45c-4541-835c-3fe9dfcc9d6b)


# Задача 4

[Скрипт](https://github.com/g-timokhin/shvirtd-example-python/blob/main/run_app.sh)

![image](https://github.com/user-attachments/assets/a2eb1080-0ee5-447f-9457-5d6475fc375b)

Выполнение скрипта для клонирования репозитория и поднятия композа

![image](https://github.com/user-attachments/assets/ac8892b7-51fe-43f4-b7a8-50b9b5c98349)

Запуск проверки сервиса, развернутого на ВМ

![image](https://github.com/user-attachments/assets/0dbf908d-193d-4c4d-bbea-f233bd414e1e)


Повторение SQL-запроса

![image](https://github.com/user-attachments/assets/aa287f41-f935-472e-8465-87906a0fba80)

# Задача 6

Используем dive для подключения к образу hashicorp/terraform:latest

![image](https://github.com/user-attachments/assets/598efa16-1de3-48e8-a69c-97d0a166a32f)

Найдем в файловой системе файл /bin/terraform
ID слоя -- blobs, Digest -- sha256:c3c3a5978391c2884975a1e49c4d3ee1e29dac201a59bf27685a1b750ad5e64a

![image](https://github.com/user-attachments/assets/473886d2-79bb-4419-8e81-d1d3a7b93968)

![image](https://github.com/user-attachments/assets/997ddf10-06b9-4372-b790-e731aa26a5a1)

Сохраним образ с помощью docker save

![image](https://github.com/user-attachments/assets/fd742a02-7e93-44f0-b9da-3a3a30ccf7b6)

Разархивируем нужный файл

![image](https://github.com/user-attachments/assets/84c8aa56-db3c-4ccc-8bb2-5713aaaa13cd)

# Задача 6.1

Копирование файла из контейнера с помощью docker cp 

![image](https://github.com/user-attachments/assets/b1118fae-86f7-48bb-be67-e8c259add098)
























