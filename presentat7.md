## Российский Университет Дружбы Народов

### Факультет Физико-Математических и Естественных Наук
###Презентация лаб7

*Дисциплина: Операционные системы*

Студент: Ясмин Бен бадр

Группа: НПИбд-02-20

Москва, 2021г.

----

##df / du

Для того, чтобы посмотреть, сколько места занимает файловая система, диск, файл или каталог, в Linux существует две команды: df и du.

###Df   
 (disk free) выводит список всех файловых систем по именам устройств с указанием размера, показывает точки монтирования и количество свободного/занятого пространства.
Синтаксис команды
**df опции файл/устройство**

###Du
Утилита du (disk usage) – используется для оценки занимаемого файлового пространства. Показывает размер файлов и каталогов, как в совокупности, так и по отдельности.
Синтаксис команды
**du опции файл/устройство**

### Цель работы

Ознакомление с инструментами поиска файлов и фильтрации текстовых данных. Приобретение практических навыков: по управлению процессами (и заданиями), по проверке использования диска и обслуживанию файловых систем.

----

### Ход работы:

1. Осуществила вход в систему, используя соответствующее имя пользователя.
 ![](https://raw.githubusercontent.com/benbaderyasmine/lab7/main/photo/New%20folder/1.png)  
 ![](https://raw.githubusercontent.com/benbaderyasmine/lab7/main/photo/New%20folder/2.png)
2. Записала в файл file.txt названия файлов, содержащихся в каталоге /etc. Дописала в этот же файл названия файлов, содержащихся в домашнем каталоге.
   ![](https://raw.githubusercontent.com/benbaderyasmine/lab7/main/photo/New%20folder/3.png)
   ![](https://raw.githubusercontent.com/benbaderyasmine/lab7/main/photo/New%20folder/3.1.png)
3. Вывела имена всех файлов из file.txt, имеющих расширение .conf, после чего записала их в новый текстовой файл conf.txt.
   ![](https://raw.githubusercontent.com/benbaderyasmine/lab7/main/photo/New%20folder/4.png)
4. Определила, какие файлы в домашнем каталоге имеют имена, начинающиеся с символа c. Есть несколько вариантов, как сделать это:
![](https://raw.githubusercontent.com/benbaderyasmine/lab7/main/photo/New%20folder/4.png)
5. Вывела на экран (по странично) имена файлов из каталога /etc, начинающиеся с символа h.
6. Запустила в фоновом режиме процесс, который будет записывать в файл ~/logfile файлы, имена которых начинаются с log.
7. Удалила файл ~/logfile.
1[](https://raw.githubusercontent.com/benbaderyasmine/lab7/main/photo/New%20folder/5.png)
8. Запустила из консоли в фоновом режиме редактор gedit.
![](https://raw.githubusercontent.com/benbaderyasmine/lab7/main/photo/New%20folder/6.png)
![](https://raw.githubusercontent.com/benbaderyasmine/lab7/main/photo/New%20folder/7.png)
9.  Определила идентификатор процесса gedit, используя команду ps, конвейер и фильтр grep. Более простым способом определить этот идентификатор не получилось.
![](https://raw.githubusercontent.com/benbaderyasmine/lab7/main/photo/New%20folder/8.png)
10. Прочела справку (man) команды kill, после чего использовал её для завершения процесса gedit.
![](https://raw.githubusercontent.com/benbaderyasmine/lab7/main/photo/New%20folder/mN.png)
12. Выполнила команды df и du, предварительно получив более подробную информацию об этих командах, с помощью команды man.
![](https://raw.githubusercontent.com/benbaderyasmine/lab7/main/photo/New%20folder/ddf.png)
![](https://raw.githubusercontent.com/benbaderyasmine/lab7/main/photo/New%20folder/df.png)
![](https://raw.githubusercontent.com/benbaderyasmine/lab7/main/photo/New%20folder/man%20du.png)
13. Воспользовавшись справкой команды find, вывел имена всех директорий, имеющихся в домашнем каталоге.
 ![](https://raw.githubusercontent.com/benbaderyasmine/lab7/main/photo/New%20folder/find.png)

----

### Вывод

Ознакомился с инструментами поиска файлов и фильтрацией текстовых данных, приобрела практические навыки: по управлению процессами (и заданиями), по проверке использования диска и обслуживанию файловых систем.

----

