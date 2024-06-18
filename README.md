# Домашнее задание к занятию 1 «Disaster recovery и Keepalived» - `Трошин Константин`


---

### Задание 1

##### Процесс выполнения
1. Запустите два simple python сервера на своей виртуальной машине на разных портах
2. Установите и настройте HAProxy, воспользуйтесь материалами к лекции по ссылке
3. Настройте балансировку Round-robin на 4 уровне.


##### Требования к результаты
На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy.

### Решение

![alt text](https://github.com/Semergal/sflt/blob/master/img/Screenshot_1.jpg)
![alt text](https://github.com/Semergal/sflt/blob/master/img/Screenshot_2.jpg)



### Задание 2

#### Процесс выполнения
1. Запустите три simple python сервера на своей виртуальной машине на разных портах
2. Настройте балансировку Weighted Round Robin на 7 уровне, чтобы первый сервер имел вес 2, второй - 3, а третий - 4
3. HAproxy должен балансировать только тот http-трафик, который адресован домену example.local


#### Требования к результаты
На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy c использованием домена example.local и без него.



### Решение

![alt text](https://github.com/Semergal/sflt/blob/master/img/Screenshot_3.jpg)
![alt text](https://github.com/Semergal/sflt/blob/master/img/Screenshot_4.jpg)



