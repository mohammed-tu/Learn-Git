<div dir="rtl">
 
# تحديث رسالة ال commit 

امر لتغيير محتوى الرسالة المكتوبة خلال الامر commit

من خلال الامر التالي:


<div dir="ltr">
  
```
  git commit --amend -m "message"
```  
  
  
```
$ git log
commit 3d68eca788db5f75d2dd2452afe684d073a8a81f (HEAD -> master)
Author: Mohammed <Mohammed@example.com>
Date:   Wed Apr 14 14:14:50 2021 +0300

    add: hi.txt
$ git commit --amend -m "change: message"
[master 9837eb2] change: message
 Date: Wed Apr 14 14:14:50 2021 +0300
 1 file changed, 1 insertion(+)
 create mode 100644 hi.txt
$ git log
commit 9837eb2a22603faa61a8c44ab4f80215884e2f8a (HEAD -> master)
Author: Mohammed <Mohammed@example.com>
Date:   Wed Apr 14 14:14:50 2021 +0300
    change: message
```
