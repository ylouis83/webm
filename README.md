webm
====

mysql web key performance monitor

webm was update to webm_v2 version

webm is a tool that show significant statistic value for databases (key value like redosize,QPS,TPS and so so)

webm support oracle mysql and mongodb at present

1.for oracle : agent was wrote by perl and you need install perl-DBI and MYLSQ-DBD for data uploading.

2.for mysql : agent was wrote by C language and you will upload data to monitor server directly 

3.for mongodb: agent was wrote by python and stored in local mongodb database. The format of statistic was json.

All of statistics was uploaded to monitor server (mysql database) ,you can keep them for a long time for future analysis.


On web site we use javascripts and PHP to display graph so you need install all of them


Environment need:

Linux version 5+  php5 Apache server 

You can also run this tool on windows platform (install xampp )

![image](https://cloud.githubusercontent.com/assets/1445708/4434723/aa6eb64a-4722-11e4-83f3-564ef86cbca5.png)

![image](https://cloud.githubusercontent.com/assets/1445708/4434725/bb597ab2-4722-11e4-889d-758d44fec16e.png)



