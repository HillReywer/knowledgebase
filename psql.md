#### Для 12 PG

##### Отстрелить все соединения к указанной БД

SELECT pg_terminate_backend(pid)
FROM pg_stat_activity
WHERE datname = 'mydb';
