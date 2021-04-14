<div dir="rtl">

# الامر `git add`

أمر لنقل الملف من مرحلة الغبر متتبع الى مرحلة تنظيم الملفات 
من خلال الامر التالي :


<div dir="ltr">
  
  ```
$ git status
On branch master
No commits yet
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        hi.txt
nothing added to commit but untracked files present (use "git add" to track)

$ git add hi.txt
warning: LF will be replaced by CRLF in hi.txt.
The file will have its original line endings in your working directory

$ git status
On branch master
No commits yet
Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   hi.txt
  ```
</div>
