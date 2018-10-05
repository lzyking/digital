## 针对Joychat 服务器的 Zabbix监控进行调整
##### 时间：2018-10-05

下面模板中的 interval check 都改成10s了。

 - [x] Template App Nginx_custom  （由 30 改成10）
 
 - [x] Template WORKPLUS PORT 8020 8021 （由 30 改成 10）
		 - [x] workplus port 8020 is connection 	
		 - [x] workplus port 8020 is listen
		 - [x] workplus port 8021 is connection 	
		 - [x] workplus port 8021 is listen
		 - [x] workplus process

Template App Zabbix Agent
没改

 - [x] Template App MySQL
		 - [x] 除了 MySQL version 是1小时没有改，其他都由 1m 改成 10s了。
 
 - [x] Template App MongoDB_Custom 
		 - [ ] 都由 30s 改成 10s了

 - [x] Template APP Redis_Custom
	 - redis_used_memory_human 原来设置的就是 10s 没有变 		
	 - 其他的都由 30s 改成了 10s

 - [x] Template APP Zookeeper_Custom
	 - 都由 30s 改成了 10s

<!--stackedit_data:
eyJoaXN0b3J5IjpbMTQ3Mjg4NjJdfQ==
-->