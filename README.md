# Домашнее задание Сартисона Евгения №6 #


## (1) Развернуть Постгрес на ВМ ##
создал самую простую VM в YC 

![image](https://github.com/user-attachments/assets/9b598d4f-1691-4c15-a87b-f4cf33232028)

установил Postgres с настройками по умолчанию
>sudo apt install curl ca-certificates

>sudo install -d /usr/share/postgresql-common/pgdg

>sudo curl -o /usr/share/postgresql-common/pgdg/apt.postgresql.org.asc --fail https://www.postgresql.org/media/keys/ACCC4CF8.asc

>sudo sh -c 'echo "deb [signed-by=/usr/share/postgresql-common/pgdg/apt.postgresql.org.asc] https://apt.postgresql.org/pub/repos/apt $(lsb_release -cs)-pgdg main" > /etc/apt/sources.list.d/pgdg.list'

>sudo sh -c 'echo "deb [arch=amd64 signed-by=/usr/share/postgresql-common/pgdg/apt.postgresql.org.asc] https://apt.postgresql.org/pub/repos/apt noble-pgdg main" > /etc/apt/sources.list.d/pgdg.list'

>sudo apt update

>sudo apt install postgresql-13 postgresql-client-13
![image](https://github.com/user-attachments/assets/5fcc0e98-235a-4fc7-9380-842f2606bbc2)



## (2) Протестировать pg_bench ##


## (3) Выставить оптимальные настройки ##


## (4) Проверить насколько выросла производительность ##


## (5) Настроить кластер на оптимальную производительность не обращая внимания на стабильность БД ##
