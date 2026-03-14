University: [ITMO University](https://itmo.ru/ru/)\
Faculty: [FICT](https://fict.itmo.ru)\
Course: [Введение в веб технологии](https://itmo-ict-faculty.github.io/introduction-in-web-tech/)\
Year: 2025/2026\
Group: U4125\
Author: Barvinskaya Mariya Borisovna \
Lab: Lab3\
Date of create: 13.03.2026\
Date of finished:\

# Ход работы
1) Создала файл prometheus/prometheus.yml с информацией о частоте сбора метрик, метриками prometheus и метриками системы \
фото 1 \
2) Запустила контейнер Node Exporter и проверила его работу: \
фото 2 \
3) Создала том prometheus-data, для работы с grafana создала общую сеть monitoring \
4) Работа prometheus на локальном хосте: \
фото 3 \
5) Создала том grafana-data и запустила контейнер: \
Фото 4 \
6) На локальном хосте графана работает: \
фото 5 \
7) Залогинилась под админом в графане, добавила источник данных prometheus: \
фото 6 \
8) В prometheus проверила доступность node-exporter: \
фото 7




Трудности: долго мучилась с заапуском Prometheus. Через Git Bash не получалось, разбиралась с логами: все время выдавал "Error loading config". Получилось запустить через командную строку (cmd) 
