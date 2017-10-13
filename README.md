文字雲實作
*資料:			data.txt
*logstash conf:	tag_cloud_etl.conf

1. ES狀態檢查，利用netstat -an | more 檢查9200 port 有沒有開
2. Kibana狀態檢查，利用netstat -an | more 5601 port 有沒有開
3. 執行指令：
C:/dev/ELK_lesson/lab/logstash/bin/logstash.bat -f //C:/dev/ELK_lesson/es_lesson_1013/tag_cloud_etl.conf --path.data C:/dev/ELK_lesson/lab/tmp