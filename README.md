# TerminalGitBash

Homework №1 linux terminal (GitBash) commands

1. Посмотреть где я.  
`$ pwd`
3. Создать папку.  
`$ mkdir papka_hw1`
5. Зайти в папку.  
`$ cd papka_hw1`
7. Создать 3 папки.  
`$ mkdir papka_1`  
`$ mkdir papka_2`  
`$ mkdir papka_3`
9. Зайти в любоую папку.  
`$ cd papka_3`
11. Создать 5 файлов (3 txt, 2 json).  
`$ touch txt1.txt`  
`$ touch txt2.txt`  
`$ touch txt3.txt`  
`$ touch js1.json`  
`$ touch js2.json`
13. Создать 3 папки.  
`$ mkdir papka_1`  
`$ mkdir papka_2`  
`$ mkdir papka_3`
15. Вывести список содержимого папки.  
`$ ls -la # "-la" - показывает весь список файлов в корне папки.`
17. Открыть любой txt файл.  
`$ vim txt1.txt`
19. Написать туда что-нибудь, любой текст.  
`i # нажать для начала редактирования документа.`  
`1.yabloko`  
`2.grysha`  
`3.ananas`  
`4.banan`
21. Сохранить и выйти.  
`Esc`  
`:x`  
`Enter`
23. Выйти из папки на уровень выше.  
`$ cd ../`
25. Переместить любые 2 файла, которые вы создали, в любую другую папку.  
`cd papka_3`  
`mv txt1.txt papka_1`  
`mv txt2.txt papka_1`
27. Скопировать любые 2 файла, которые вы создали, в любую другую папку.  
`cp js1.json papka_2`  
`cp js2.json papka_2`
29. Найти файл по имени.  
`$ find -name txt1.txt # "-name" - поиск по имени.`
31. Просмотреть содержимое в реальном времени (команда grep) изучите как она работает.  
`$ cd papka_1`  
`$ grep ananas txt1.txt`
33. Вывести несколько первых строк из текстового файла.  
`$ head -n 3 txt1.txt # "-n" - вывод строк по количеаству, "3" - сколько первых строк нужно вывести.`
35. Вывести несколько последних строк из текстового файла.  
`$ tail -n 2 txt1.txt # "-n" - вывод строк по количеству, "2" - сколько последних строк нужно вывести.`
37. Просмотреть содержимое длинного файла (команда less) изучите как она работает.  
`$ less txt1.txt`  
`/banan # поиск с верху в низ по тексту.`  
`?grysha # поиск в любом месте текста.`  
`q # выход из поисковика.`
39. Вывести дату и время.  
`$ date`

Homework №1*

1. Отправить http запрос на сервер. http://162.55.220.72:5005/terminal-hw-request
2. Написать скрипт который выполнит автоматически пункты: 3, 4, 5, 6, 7, 8, 13.
