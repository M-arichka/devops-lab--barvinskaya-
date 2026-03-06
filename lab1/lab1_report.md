University: [ITMO University](https://itmo.ru/ru/)\
Faculty: [FICT](https://fict.itmo.ru)\
Course: [Введение в веб технологии](https://itmo-ict-faculty.github.io/introduction-in-web-tech/)\
Year: 2025/2026\
Group: U4125\
Author: Barvinskaya Mariya Borisovna \
Lab: Lab1\
Date of create: 05.03.2026\
Date of finished:\

Ход работы:
## 1)Установила Docker Desktop
Проверила установку командой docker --version:

<img width="333" height="42" alt="image" src="https://github.com/user-attachments/assets/2a4f6ccc-b0f0-4d08-a761-75d2189012ba" />

Запустила тестовый контейнер: docker run hello-world:

<img width="505" height="644" alt="image" src="https://github.com/user-attachments/assets/7e92bb7e-5c23-4c03-8a1e-7bb32b9d512a" />

Изучила базовые команды: docker images (Локальные образы), docker ps (Список запущенных контейнеров), docker ps -a (Список всех контейнеров):

<img width="500" height="301" alt="image" src="https://github.com/user-attachments/assets/a6ea5830-e7de-4656-9725-145e4c65ab90" />

## 2)Провела работу с готовыми образами
Скачала образ Ubuntu:

<img width="620" height="139" alt="image" src="https://github.com/user-attachments/assets/910d38ef-9139-4672-90ac-82301f5258ee" />

Запустила интерактивный контейнер:

<img width="707" height="756" alt="image" src="https://github.com/user-attachments/assets/8bd2aed4-d65a-4b9d-8041-69129b71906b" />

Запустила интерактивно контейнер, установила пакет curl, проверила установку curl и вышла из контейнера:

<img width="690" height="449" alt="image" src="https://github.com/user-attachments/assets/7b8c4e6b-4d85-4902-af05-4f206cf3d03e" />

## 3)Запустила веб-сервер
Запустила контейнер с nginx:

<img width="580" height="329" alt="image" src="https://github.com/user-attachments/assets/e892d2fe-535a-4e6b-a46d-f710add8b585" />

Проверила работу на локальном хосте, все корректно:
<img width="773" height="320" alt="image" src="https://github.com/user-attachments/assets/547e622b-6807-4b31-b6e8-076560bb1dfb" />

Посмотрела логи контейнера:

<img width="716" height="580" alt="image" src="https://github.com/user-attachments/assets/c2245a47-020a-4ccf-af55-3b46b24a4984" />
 
 Подключилась к контейнеру и выполнила команду ls:
 
<img width="527" height="167" alt="image" src="https://github.com/user-attachments/assets/a9b05064-9ead-49c6-a45c-d12f6559981c" />

## 4)Управление контейнерами
Посмотрела список запущенных контейнеров (добавился nginx), список всех контейнеров, остановила, запустила и снова остановила контейнер web-server, удалила контейнер и образ:

<img width="730" height="719" alt="image" src="https://github.com/user-attachments/assets/d64ad6b0-e29f-45ce-857e-4197663f4c2a" />

## 5)Работа с томами
Создала том, запустила контейнер с томом:

<img width="630" height="106" alt="image" src="https://github.com/user-attachments/assets/9b447823-cb13-46b0-9ada-c1088089dab2" />

Подключилась к контейнеру, создала файл в томе, удалила контейнер и создать новый с тем же томом. Файл сохранился: 

<img width="614" height="102" alt="image" src="https://github.com/user-attachments/assets/7c1ad541-78d2-4ca3-ba23-fff2969f24d6" />
<img width="634" height="274" alt="image" src="https://github.com/user-attachments/assets/616015e4-954b-4660-9352-a44d505f9c7d" />
