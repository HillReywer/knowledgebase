# Enable slow query log
## Turn on

SET GLOBAL slow_query_log_file = '/var/log/mysql/slow-query.log';
SET GLOBAL long_query_time = 2; (time in sec)
SET GLOBAL slow_query_log = 'ON';
FLUSH LOGS;

## Turn off

SET GLOBAL slow_query_log = 'OFF';
FLUSH LOGS;