[HW_2 : Terminal. Format : JSON](https://github.com/Vitaly-chek/JSON)

[HW_2 : Terminal. Format : XML](https://github.com/Vitaly-chek/XML)

[HW_2 : Terminal. Format : TXT](https://github.com/Vitaly-chek/TXT)

[HW_1 : Git](https://github.com/Vitaly-chek/Git)

---


# HW_1 : Terminal

1. Посмотреть где я - `pwd`;

2. Создать папку - `mkdir dz_1`;

3. Зайти в папку - `cd dz_1`;

4. Создать 3 папки - `mkdir les_1 les_2 les_3`;

5. Зайти в любоую папку - `cd les_2`;

6. Создать 5 файлов (3 txt, 2 json) - `touch doc_1.txt doc_2.txt doc_3.txt doc_4.json doc_5.json`;

7. Создать 3 папки - `mkdir fol_1 fol_2 fol_3`;

8. Вывести список содержимого папки - `ls (ls -la)`;

9. Открыть любой txt файл - `vim doc_1.txt`;

10. Написать туда что-нибудь, любой текст - `на "винде" нажал 'i' и написал текст :)`;

11. Сохранить и выйти - `esc -> :wq`;

12. Выйти из папки на уровень выше - `cd ..`;

13. Переместить любые 2 файла, которые вы создали, в любую другую папку - `mv doc_1.txt doc_2.txt fol_1/`;

14. скопировать любые 2 файла, которые вы создали, в любую другую папку - `cp doc_1.txt doc_2.txt fol_1/`;

15. Найти файл по имени - `find -name doc_1.txt`;

16. Просмотреть содержимое в реальном времени (команда grep) изучите как она работает - `ail -n+1 doc_1.txt`;

17. Вывести несколько первых строк из текстового файла - `head -n3 doc_1.txt`;

18. Вывести несколько последних строк из текстового файла - `tail -n2 doc_1.txt`;

19. Просмотреть содержимое длинного файла (команда less) изучите как она работает - `less doc_1.txt`;

20. Вывести дату и время - `date`;

## Задание со *

1. Отправить http запрос на сервер;
---

```
curl http://162.55.220.72:5005/object_info_3?name=Vadim&age=32&salary=1000
```
2. Написать скрипт который выполнит автоматически пункты 3, 4, 5, 6, 7, 8, 13;
---

```
#! /bin/bash

cd prob
mkdir les_1 les_2 les_3
cd les_2
mkdir fol_1 fol_2 fol_3
ls -la
touch doc_1.txt doc_2.txt
ls -la
mv doc_1.txt doc_2.txt fol_1/
```
