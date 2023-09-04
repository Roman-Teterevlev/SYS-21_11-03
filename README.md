### Roman Teterevlev

### ELK

### Задание 1. Elasticsearch 

Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный. 

*Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name*.

### Ответ:

![alt text](https://github.com/Roman-Teterevlev/SYS-21_11-03/blob/main/11-03_1.1.png)

---

### Задание 2. Kibana

Установите и запустите Kibana.

*Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty*.

### Ответ:

![alt text](https://github.com/Roman-Teterevlev/SYS-21_11-03/blob/main/11-03_2.1.png)

---

### Задание 3. Logstash

Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch. 

*Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.*

### Ответ:

См. logstash-trouble.md

---

### Задание 4. Filebeat. 

Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat. 

*Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.*

### Ответ:

![alt text](https://github.com/Roman-Teterevlev/SYS-21_11-03/blob/main/11-03_4.1.png)
![alt text](https://github.com/Roman-Teterevlev/SYS-21_11-03/blob/main/11-03_4.2.png)

---

