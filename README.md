# MusiX
Это бот, который выдает MP3 файлы с Яндекс Музыки прямо в телеграме, также реализовано получение треков из "Чарта" Яндекс Музыки.
# Инструкция
## Установка:
### Установите репозиторий:
```
git clone https://github.com/Leolox228/MusiX-tg-.git
```
### Перейдите в папку с репозиторием:
```
cd MusiX-tg-
```
### Установите зависимости:
```
pip install -r requirements.txt
```
### Измените .env (в зависимости от вашей системы)
### Запустите бота
```
python3 main.py
```
## Инлайн режим:
### Если пользватель ничего не ввел выводится плашка с мемом)
![image](https://github.com/user-attachments/assets/0c70fbf0-d06f-4f8b-b679-03f1bf5b3463)
### Тоже самое происходит, если пользователь ввел несуществующее название трека:
![image](https://github.com/user-attachments/assets/ddb63846-f83e-44cc-bbec-eb5f897585a6)
### Если пользователь ввёл запрос, то выдаётся список песен по этому запросу:
![image](https://github.com/user-attachments/assets/ac7690f0-5262-423d-9c67-75bd7defa09a)
### После выбора нужной песни от имени пользователя отправляется сообщение с 2 кнопками:
![image](https://github.com/user-attachments/assets/904824d0-33e1-4f0e-afba-30e8ef1de561)
### При нажатии на "Скачать" появится меню с 1 треком, после нажатия на который будет отправлена песня:
![image](https://github.com/user-attachments/assets/881d889b-bd48-4ebd-841f-199fd075b788)
### При нажатии на "Инфо" появится меню с 1 плашка, после нажатия на которую будет отправлена информация о треке:
![image](https://github.com/user-attachments/assets/74c2f2d8-cf21-4eb0-a8c5-9862d443822f)
### Вы получаете такую информацию, как:
#### Название
#### Альбом
#### Жанр
#### Год выпуска
### Получить текст можно при нажатии на кнопку "Текст":
![image](https://github.com/user-attachments/assets/245b11f7-4391-467f-bc38-3a1959e69f18)
## Сообщения боту:
### При отправке боту команды /start он отправляет сообщение с двумя кнопками:
![image](https://github.com/user-attachments/assets/26ed2e96-2669-4206-8d89-2a3c24c52a50)
### Если нажать на "Запустить", то запуститься инлайн режим, о котором писал выше:
![image](https://github.com/user-attachments/assets/b1d06081-45c1-4929-9e71-963a562fa67a)
### При нажатии на "Чарт", сообщение измениться на интерактивное меню с треками из "Чарта" Яндекс Музыки:
![image](https://github.com/user-attachments/assets/f3f8bb52-0369-4e2f-ac8d-ad1bfd13e558)
