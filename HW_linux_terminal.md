## Homework 1

| Задание | Решение |
| --- |  --- |
|1) Посмотреть где я |```pwd ```|
|2) Создать папку |```mkdir hw```|
|3) Зайти в папку |```cd hw```|
|4) Создать 3 папки |```mkdir hw1 hw2 hw3```|
|5) Зайти в любоую папку    |```cd hw1```|
|6) Создать 5 файлов (3 txt, 2 json) |```touch hw1.txt hw2.txt hw3.txt touch hw4.json hw5.json```|
|7) Создать 3 папки      |```mkdir max max1 max2```|
|8) Вывести список содержимого папки   |```ls -la```|
|10) Открыть любой txt файл      |```vim hw1.txt```|
|11) Написать туда что-нибудь, любой текст  |```insert```|
|12) Сохранить и выйти  |```ESC, :wq```|
|13) Выйти из папки на уровень выше      |```cd ..```|
|14) Переместить любые 2 файла, которые вы создали, в любую другую папку   |```mv hw1.txt hw4.json max/```|
|15) Скопировать любые 2 файла, которые вы создали, в любую другую папку   |```cp hw2.txt hw5.json max1/```|
|16) Найти файл по имени    | ```find -name hw2.txt```    |
|17) Просмотреть содержимое в реальном времени |```grep vadim hw1.txt```|
|18) Вывести несколько первых строк из текстового файла   |```head -n2 hw1.txt```|
|19) Вывести несколько последних строк из текстового файла    |```tail -n2 hw1.txt```|
|20) Просмотреть содержимое длинного файла     |```less -s hw1.txt```|
|21) Вывести дату и время     | ```date```     |
|22) Объеденить 2 файла     |```cat hw2.txt hw3.txt > hw10.txt```|
|23) Отправить http запрос на сервер.     | http://162.55.220.72:5005/object_info_3?name=Vadim&age=32&salary=1000 - ```curl```|
|24) Написать скрипт который выполнит автоматически пункты 3, 4, 5, 6, 7, 8, 13 |```nano skript1.sh```|

```
#!/bin/bash
mkdir skript
cd skript
mkdir skript_f1 skript_f2 skript_f3
cd skript_f3
touch skr_text1.txt skr_text2.txt skr_text3.txt skr_js1.json skr_js2.json
mkdir skr1 skr2 sk3
ls -la
cp skr_text1.txt skr_js1.json skr1
```
```
ctrl^x ---> y(yes) ---> enter

bash skript1.sh
```