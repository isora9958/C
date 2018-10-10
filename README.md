# C 程式開發
>* Windows平台:Dev-c++, Visual studio 2017 community
>* Linux 平台: gcc

使用Linux 平台C程式開發:
```
1.編輯程式: gedit  myc_1_1.c
2.編譯: gcc myc_1_1.c -o myc_1_1
3.執行:./myc_1_1
```
### 說明下列程式的關鍵

```
/* myc_1_1, 我的第一個C程式碼 */ 
#include <stdio.h>
#include <stdlib.h>
int main(void)
{
   printf("Hello 偉大的恩師!\n");   	/* 印出Hello 偉大的恩師! 字串 */
   printf("Hello Taiwan!\n");        /* 印出Hello Taiwan! 字串 */   
   
   system("pause");
   return ;
   printf("Hello World!\n");
}
```
```
Question 1:#include <stdio.h>
include 是何意義??
stdio有何用途?
std英文全名為何?
i是何意義??o是何意義??
h = header =標頭檔有何用途? 
https://zh.wikipedia.org/wiki/Stdio.h
```
```
Question 2:#include <stdlib.h>
stdlib有何用途?
std英文全名為何?
lib是何意義??
https://zh.wikipedia.org/wiki/Stdlib.h
```
```
Question 3:   system("pause");
stdlib有何用途?
std英文全名為何?
lib是何意義??
https://zh.wikipedia.org/wiki/Stdlib.h
```
```
/* myc_1_1, 我的第一個C程式碼 */ 
#include <stdio.h>
#include <stdlib.h>
int main(void)
{
   printf("Hello 恩師!\n");   	/* 印出Hello 恩師! 字串 */
   printf("Hello Taiwan!\n");   /* 印出Hello Taiwan! 字串 */   
   
//  system("pause");
   return ;
}
```
root@kali:~# gedit myc_1_1.c
root@kali:~# gcc myc_!_!.c -o myc_!_!
bash: !_!.c: event not found
root@kali:~# gcc myc_1_1.c -o myc_1_1
myc_1_1.c: In function ‘main’:
myc_1_1.c:10:4: error: ‘rreturn’ undeclared (first use in this function)
    rreturn ;
    ^~~~~~~
myc_1_1.c:10:4: note: each undeclared identifier is reported only once for each function it appears in
root@kali:~# ^C
root@kali:~# 

root@kali:~# gcc myc_1_1.c -o myc_1_1
myc_1_1.c: In function ‘main’:
myc_1_1.c:10:4: warning: ‘return’ with no value, in function returning non-void
    return ;
    ^~~~~~
myc_1_1.c:4:5: note: declared here
 int main(void)
     ^~~~
root@kali:~# 

            http://www.runoob.com/python/python-100-examples.html
