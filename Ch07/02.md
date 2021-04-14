<div dir="rtl">

# الدمج المباشر 

وهو العملية المباشرة للدمج بحيث يكون التعديل موجود على الفرع ويتم دمجه الى الملف الرئيسي 

من خلال الأمر التالي :
 مع ملاحظة أن الامر يكون من خلال الملف الرئيسي

<div dir="ltr">

```
$ git merge new-branch
```
<div dir="rtl">

مثال توضيحي :

<div dir="ltr">

```
$ git log
commit 9837eb2a22603faa61a8c44ab4f80215884e2f8a (HEAD -> master, dev-new-branch)
Author: Mohammed <Mohammed@example.com>
Date:   Wed Apr 14 14:14:50 2021 +0300

    change: message

$ git checkout dev-new-branch
Switched to branch 'dev-new-branch'

$ echo hi from branch > hi-from-branch.txt

$ git add hi-from-branch.txt
warning: LF will be replaced by CRLF in hi-from-branch.txt.
The file will have its original line endings in your working directory

$ git commit -m "from branch"
[dev-new-branch 70672b6] from branch
 1 file changed, 1 insertion(+)
 create mode 100644 hi-from-branch.txt

$ git log
commit 70672b62fecad8fd82c968fc62a18e5013f9a1da (HEAD -> dev-new-branch)
Author: Mohammed <Mohammed@example.com>
Date:   Wed Apr 14 15:56:49 2021 +0300

    from branch

commit 9837eb2a22603faa61a8c44ab4f80215884e2f8a (master)
Author: Mohammed <Mohammed@example.com>
Date:   Wed Apr 14 14:14:50 2021 +0300

    change: message

$ git checkout master
Switched to branch 'master'

$ git log
commit 9837eb2a22603faa61a8c44ab4f80215884e2f8a (HEAD -> master)
Author: Mohammed <Mohammed@example.com>
Date:   Wed Apr 14 14:14:50 2021 +0300

    change: message

$ git merge dev-new-branch
Updating 9837eb2..70672b6
Fast-forward
 hi-from-branch.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 hi-from-branch.txt

$ git log
commit 70672b62fecad8fd82c968fc62a18e5013f9a1da (HEAD -> master, dev-new-branch)
Author: Mohammed <Mohammed@example.com>
Date:   Wed Apr 14 15:56:49 2021 +0300
    from branch
commit 9837eb2a22603faa61a8c44ab4f80215884e2f8a
Author: Mohammed <Mohammed@example.com>
Date:   Wed Apr 14 14:14:50 2021 +0300

    change: message
```
