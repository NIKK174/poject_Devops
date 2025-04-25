1. [Перейти к Part 1](#part-1)  
2. [Перейти к Part 2](#part-2)
3. [Перейти к Part 3](#part-3) 
4. [Перейти к Part 4](#part-4)  
5. [Перейти к Part 5](#part-5) 
6. [Перейти к Part 6](#part-6) 
7. [Перейти к Part 7](#part-7) 
8. [Перейти к Part 8](#part-8) 
9. [Перейти к Part 9](#part-9) 
10. [Перейти к Part 10](#part-10) 
11. [Перейти к Part 11](#part-11) 
12. [Перейти к Part 12](#part-12) 
13. [Перейти к Part 13](#part-13) 
14. [Перейти к Part 14](#part-14) 
15. [Перейти к Part 15](#part-15) 


1. ### Part 1  
* вывод команды cat /etc/issue:

![img1](../src/images/1.png)





2. ### Part 2
* создание нового пользователя:

![img2](../src/images/2.png)

![img3](../src/images/3.png)





3. ### Part 3
* Изменение названия машины вида user-1:

![img4](../src/images/4.png)

![img5](../src/images/5.png)

* Установка временной зоны:

![img6](../src/images/6.png) 

* Выввод названий сетевых интерфейсов:

![img7](../src/images/7.png)

    * lo(loopback) - виртуальный интерфейс, который по умолчанию присутствует в любом linux. Используется для отладки сетевых программ и запуска серверных приложений. C lo всегда связан ip 127.0.0.1

* Получение ip-адреса от DHCP(?):

![img8](../src/images/8.png)

    * DHCP - Dynamic Host Configuration Protocol. 

* Внешний ip-адрес шлюза(?):

![img9](../src/images/9.png)

* Внутренний ip-адрес шлюза(?):

![img9](../src/images/7.png)

* Задал статичные настройки ip, gw, dns(1.1.1.1 и 8.8.8.8):

![img10](../src/images/10.png)

![img11](../src/images/11.png)

![img12](../src/images/12.png)





4. ### Part 4
* Обновил системные пакеты:

![img13](../src/images/13.png)





5. ### Part 5
* Разрешил пользователю, созданному в [Part 2](#part-2),выполнять команду sudo:

![img14](../src/images/14.png)

    *SUDO (Super User DO) - утилита, которая временно предоставляет привелегии root

 * Поменял hostname ОС от имени пользователя, созданного в пункте [Part 2](#part-2) (используя sudo).

![img15](../src/images/15.png)

![img16](../src/images/16.png)






6. ### Part 6
* Настроил службу автоматической синхронизации времени:

![img17](../src/images/17.png)

![img18](../src/images/18.png)

![img19](../src/images/19.png)






7. ### Part 7
* Установка vim, nano, joe:

![img20](../src/images/20.png)

* test_vim.txt:

![img21](../src/images/21.png)

![img22](../src/images/22.png)

    * для выхода: :wq - сохранить и выйти

* test_nano.txt:

![img23](../src/images/23.png)

![img24](../src/images/24.png) 

    * для выхода: ctrl + o - сохранить, ctrl + x -  выход

* test_joe.txt:

![img25](../src/images/25.png)

![img26](../src/images/26.png) 

    * для выхода: ctrl + k - сохранить, ctrl + x -  выход


  Используя каждый из трех выбранных редакторов, открыл файл на редактирование, отредактировал файл, заменив никнейм на строку «21 School 21», закрыл файл без сохранения изменений:

* test_vim.txt:

![img27](../src/images/27.png)

    * для выхода без сохранения: :q!

* test_nano.txt:

![img28](../src/images/28.png)

    * для выхода без сохранения: ctrl + x, n

* test_joe.txt:

![img29](../src/images/29.png)

    * для выхода без сохранения: ctrl + c, y   


* Поиск по файлу + замена слова

* test_vim.txt:

![img30](../src/images/30.png)

    * поиск по файлу: /слово которое ищем
    * замена в файле:

![img31](../src/images/31.png)


* test_nano.txt:

![img32](../src/images/32.png)

    * поиск по файлу: ctrl + w слово которое ищем
    * замена в файле: ctrl + \, вводим что хотм заменить, на что заменить 

![img33](../src/images/33.png)

* test_joe.txt:

![img34](../src/images/34.png)

    * поиск по файлу: ctrl + k, f, вводим слово которое ищем, B
    * замена в файле: ctrl + k, f, что заменить, R, на что заменить, y

![img35](../src/images/35.png)  