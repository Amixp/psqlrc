# psqlrc
psqlrc for postgresql

И есть запросы для администратора:

:settings — Server Settings 

:conninfo — Server connections

:activity — Server activity

:locks — Lock info

:waits — Waiting queires

:queries

:dbsize — Database Size

:tablesize — Tables Size

:uselesscol — Useless columns

:uptime — Server uptime

:buffer_cache_hit_ratio

:menu — Help Menu

\h — Help with SQL commands

\? — Help with psql commands



Чтобы выполнить какой-либо из этих запросов, нужно набрать двоеточие, пару первых символов какой-либо команды и нажать клавишу Tab, сработает автозаполнение и дальше нужно только Enter нажать для выполнения соответствующего запроса. Например:

:settings

Или вот:

:dbsize
