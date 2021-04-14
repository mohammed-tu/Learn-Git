<div dir="rtl">
 
 # إعادة الملفات من من مرحلة Staged 
 
 إعادة الملف من مرحلة التنظيم الى مرحلة الملفات التي لم يتم تتبعها .
 
من خلال الامر التالي :


<div dir="ltr">
  
  ```
 $ git restore --staged file.txt
  ```
  
<div dir="rtl">
  
مثال على ذلك :
  

<div dir="ltr">
  
  ```
$ echo hello > hello.txt
$ git add hello.txt
warning: LF will be replaced by CRLF in hello.txt.
The file will have its original line endings in your working directory
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   hello.txt
$ git restore --staged hello.txt
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        hello.txt
nothing added to commit but untracked files present (use "git add" to track)
  ```
  
