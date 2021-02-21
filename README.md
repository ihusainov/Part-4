# Part-4
Дисковые системы

Александра, здравствуйте!
Спасибо за выполненную работу!

Давайте попробуем по шагам, вы в задание закрепите свои картинки, что у вас получилось в задании 4

Нужно отключить текущие добавленные два диска в виртуальную машину и подключить два диска по 1G
Все действия произвожу от пользователя root

Далее нужно делать листинг текущих дисков

![](https://github.com/ihusainov/Part-4/blob/main/Pic/1.png)

Добавил в систему диски, разметил для LVM

![](https://github.com/ihusainov/Part-4/blob/main/Pic/2.png)

Cоздал VG добавил диск sdb

![](https://github.com/ihusainov/Part-4/blob/main/Pic/3.png)

Создал две логические группы

![](https://github.com/ihusainov/Part-4/blob/main/Pic/4.png)

Cоздал файловую систему xfs на обоих томах

![](https://github.com/ihusainov/Part-4/blob/main/Pic/5.png)

Монтирую оба раздела в систему

![](https://github.com/ihusainov/Part-4/blob/main/Pic/6.png)

Добавляю диск sdc к vg1

![](https://github.com/ihusainov/Part-4/blob/main/Pic/7.png)

Расширяю lv2 на всё свободное пространство vg1

![](https://github.com/ihusainov/Part-4/blob/main/Pic/8.png)

Расширяю файловую систему xfs_growfs /mnt2

![](https://github.com/ihusainov/Part-4/blob/main/Pic/9.png)

Выводы комманд

![10](https://github.com/ihusainov/Part-4/blob/main/Pic/10.png)

![11](https://github.com/ihusainov/Part-4/blob/main/Pic/11.png)

![12](https://github.com/ihusainov/Part-4/blob/main/Pic/12.png)

