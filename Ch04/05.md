<div dir="rtl">

# الامر `git commit`

هو أمر لحفظ التغييرات في الملف  ونقله من كونه تحت التنظيم الى المرحلة الثالثة وهي التأكد من التغييرات للملف ، يصاحب ذلك رسالة لوصف التغييرات . 

من خلال الامر التالي :


<div dir="ltr">
  
  ```
$ git status
On branch master
No commits yet
Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   hi.txt
$ git commit -m "add: hi.txt"
[master (root-commit) 3d68eca] add: hi.txt
 1 file changed, 1 insertion(+)
 create mode 100644 hi.txt
$ git status
On branch master
nothing to commit, working tree clean

  ```
