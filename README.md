# claster1

Домашнее задание к занятию 2 «Кластеризация и балансировка нагрузки» Romanenko A.S.

Задание 1

Запустите два simple python сервера на своей виртуальной машине на разных портах
Установите и настройте HAProxy, воспользуйтесь материалами к лекции по ссылке
Настройте балансировку Round-robin на 4 уровне.
На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy.

![Screenshot_113](https://github.com/user-attachments/assets/c31dd309-bdef-4529-9340-6f753ac43e56)
![Screenshot_112](https://github.com/user-attachments/assets/7e484af3-933e-4723-9951-a217fdeb9bd8)
![Screenshot_111](https://github.com/user-attachments/assets/8d489829-0e65-4afd-94d9-dfc7fbc35afc)

Задание 2 

Запустите три simple python сервера на своей виртуальной машине на разных портах
Настройте балансировку Weighted Round Robin на 7 уровне, чтобы первый сервер имел вес 2, второй - 3, а третий - 4
HAproxy должен балансировать только тот http-трафик, который адресован домену example.local
На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy c использованием домена example.local и без него.



![Screenshot_128](https://github.com/user-attachments/assets/b4fed02f-6fb6-4d61-a569-8b5b2d088d05)
![Screenshot_129](https://github.com/user-attachments/assets/6f56ef7b-5a7f-4012-9f80-768c9899e08a)

![Screenshot_130](https://github.com/user-attachments/assets/13508daf-d78d-4fd8-86f9-a218e51f286b)
