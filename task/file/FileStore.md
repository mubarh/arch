# Хранение файлов - статичные файлы [WIP]

## Описание задачи

Спроектировать систему для хранения и получения файлов (документы, фото, текст) разных компаний

Текущее кол-во компаний 10 (прогноз измнения: x3 в горизонте 5 лет)

### Use cases

* Разовая загрузка пачки файлов
* Правила обновления для каждого файла
* Обовещение клиента о потребности обновления файла
* Версионирование (обновление не удаляет предыдущее состояние файла)
* Возможность изменения в любой момент

Клиент
* иногда обновляет (меняют версию/версионируют)
* редко удаляют
* часто читают


### Ограничения

* Размер файлов: до 20mb
* Кол-во файлов: ~ (кол-во компаний) * 5000
* Время жизни: храним всегда
* Кол-во пользователей: ~ (кол-во компаний) * (120)



# Решение

### Требование по ресурсам

Для всей системы
* CPU:
* Memory:
* Disk:


## Сетевой/Инфраструктурный слой

## Компонентный/Сервисный слой

## Модель хранения данных