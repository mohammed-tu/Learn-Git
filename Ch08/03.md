<div dir="rtl">
  
  # حذف tag 
  
  
يتم حذف tag معين عبر الامر التالي  :
 

<div dir="ltr">

```
$ git tag -d v1.0.0
```
<div dir="rtl">
  
  مثال توضيحي :
  
  
<div dir="ltr">

```
$ git tag
$ git tag v1.0.0
$ git tag v2.0.0
$ git tag
v1.0.0
v2.0.0
$ git tag -d v2.0.0
Deleted tag 'v2.0.0' (was 70672b6)
$ git tag
v1.0.0
```
