# Кластеризация и балансировка нагрузки

Задание 1

Запустите два simple python сервера на своей виртуальной машине на разных портах

![image](https://github.com/SergeyM90/clastery/assets/84016375/4e92c43e-fd06-4dde-94ab-308124fffa0b)

![image](https://github.com/SergeyM90/clastery/assets/84016375/c9e8cf0c-0b50-4ce5-a679-b6018a8ef88a)

Установите и настройте HAProxy, воспользуйтесь материалами к лекции по ссылке
Настройте балансировку Round-robin на 4 уровне.
На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy.

Ссылка HAProxy https://github.com/SergeyM90/clastery/blob/main/haproxy.cfg

![image](https://github.com/SergeyM90/clastery/assets/84016375/d4cc79f7-8fd2-4414-a8db-27119a6ab165)

![image](https://github.com/SergeyM90/clastery/assets/84016375/50c8d2af-0d52-45e7-9332-80d004204993)


Задание 2

Запустите три simple python сервера на своей виртуальной машине на разных портах.

![image](https://github.com/SergeyM90/clastery/assets/84016375/786558ad-2ab5-497d-b1f4-be6d3fe59623)

![image](https://github.com/SergeyM90/clastery/assets/84016375/0465e2af-118f-432c-9c7b-9e67c04b86b8)

![image](https://github.com/SergeyM90/clastery/assets/84016375/10c976bf-3705-40bd-a7e1-5a7339f2aafb)

Настройте балансировку Weighted Round Robin на 7 уровне, чтобы первый сервер имел вес 2, второй - 3, а третий - 4
HAproxy должен балансировать только тот http-трафик, который адресован домену example.local
На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy c использованием домена example.local и без него.

Ссылка файл HAProxy https://github.com/SergeyM90/clastery/blob/main/haproxy_2.cfg

![image](https://github.com/SergeyM90/clastery/assets/84016375/46c5b773-e22e-4cf5-8fbb-c4742a6ad870)

![image](https://github.com/SergeyM90/clastery/assets/84016375/35c0b8fa-23e5-4a3f-acb3-9716f38ebeed)

