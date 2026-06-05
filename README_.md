# Домашнее задание к занятию "`Репликация и масштабирование. Часть 1`" - `Прокопенко Игорь`


### Инструкция по выполнению домашнего задания

   1. Сделайте `fork` данного репозитория к себе в Github и переименуйте его по названию или номеру занятия, например, https://github.com/имя-вашего-репозитория/git-hw или  https://github.com/имя-вашего-репозитория/7-1-ansible-hw).
   2. Выполните клонирование данного репозитория к себе на ПК с помощью команды `git clone`.
   3. Выполните домашнее задание и заполните у себя локально этот файл README.md:
      - впишите вверху название занятия и вашу фамилию и имя
      - в каждом задании добавьте решение в требуемом виде (текст/код/скриншоты/ссылка)
      - для корректного добавления скриншотов воспользуйтесь [инструкцией "Как вставить скриншот в шаблон с решением](https://github.com/netology-code/sys-pattern-homework/blob/main/screen-instruction.md)
      - при оформлении используйте возможности языка разметки md (коротко об этом можно посмотреть в [инструкции  по MarkDown](https://github.com/netology-code/sys-pattern-homework/blob/main/md-instruction.md))
   4. После завершения работы над домашним заданием сделайте коммит (`git commit -m "comment"`) и отправьте его на Github (`git push origin`);
   5. Для проверки домашнего задания преподавателем в личном кабинете прикрепите и отправьте ссылку на решение в виде md-файла в вашем Github.
   6. Любые вопросы по выполнению заданий спрашивайте в чате учебной группы и/или в разделе “Вопросы по заданию” в личном кабинете.
   
Желаем успехов в выполнении домашнего задания!
   
### Дополнительные материалы, которые могут быть полезны для выполнения задания

1. [Руководство по оформлению Markdown файлов](https://gist.github.com/Jekins/2bf2d0638163f1294637#Code)

---

### Задание 1


master-slave:

•	операции связанны с изменением данных только на master(INSERT, UPDATE, DELETE), 

•	изменения на slave только от master

•	на slave напрямую только select

•	master так же поддерживает select, но запросы на чтение предпочтительно направлять на slave 

master-master

•	оба сервера поддерживают запросы на запись/чтение

•	сервера друг для друга одновременно и master и slave

•	изменения на одном master реплицируются на другой

•	падение одного из master не приводит к остановке всей системы


### Задание 2

https://github.com/IPro-j/netology_SDBSQL-55_home_HW_-DDL-DML-/blob/main/img/img_1.png
https://github.com/IPro-j/netology_SDBSQL-55_home_HW_-DDL-DML-/blob/main/img/img_2.png
https://github.com/IPro-j/netology_SDBSQL-55_home_HW_-DDL-DML-/blob/main/img/img_3.png
https://github.com/IPro-j/netology_SDBSQL-55_home_HW_-DDL-DML-/blob/main/img/img_4.png
https://github.com/IPro-j/netology_SDBSQL-55_home_HW_-DDL-DML-/blob/main/img/img_5.png
https://github.com/IPro-j/netology_SDBSQL-55_home_HW_-DDL-DML-/blob/main/img/img_6.png
https://github.com/IPro-j/netology_SDBSQL-55_home_HW_-DDL-DML-/blob/main/img/img_7.png
https://github.com/IPro-j/netology_SDBSQL-55_home_HW_-DDL-DML-/blob/main/img/img_8.png
https://github.com/IPro-j/netology_SDBSQL-55_home_HW_-DDL-DML-/blob/main/img/img_9.png
https://github.com/IPro-j/netology_SDBSQL-55_home_HW_-DDL-DML-/blob/main/img/img_10.png
https://github.com/IPro-j/netology_SDBSQL-55_home_HW_-DDL-DML-/blob/main/img/img_11.png
https://github.com/IPro-j/netology_SDBSQL-55_home_HW_-DDL-DML-/blob/main/img/img_12.png



`При необходимости прикрепитe сюда скриншоты
![Название скриншота](ссылка на скриншот)`

