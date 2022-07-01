# projectC4_c462
Модуль С4. Задание С4.6.2

rsyslog > filebeat > elasticsearch > kibana

nginx on server1 configured to store logs via syslog

syslog logs to file AND sends to remote server

filebeat on server2 reads syslog and sends to elasticsearch
