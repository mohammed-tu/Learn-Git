<div dir="rtl">

## الأمر `git status`

هو تتبع حالة الملف في المشروع 

من خلال الأمر التالي :

<div dir="ltr">
  
  ```
 $ git status
On branch master
No commits yet
nothing to commit (create/copy files and use "git add" to track)
  ```
<div dir="rtl">
 
 في الحالة السابقة لا يوجد أي ملف لتتبعه .


<div dir="ltr">
  
  ```
$ echo hi > hi.txt
$ git status
On branch master
No commits yet
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        hi.txt
  ```
<div dir="rtl">
 
 في الحالة السابقة يظهر الامر `git status` حالة الملف hi.txt  .


</div>
