<div dir="rtl">
  
  # ملخص تفصيلي لدورة Git 101
  
  ### ملخص مفصل لدورة Git 101 المطروحة على منصة طويق التعليمية tuwaiq.codes 
  
  
  ****
  **الفهرس**
  - مقدمة في Git
  - [لماذا نحتاج Git?](#github.com/mohammed-tu/Learn-Git/blob/main/%D9%85%D9%82%D8%AF%D9%85%D8%A9%20%D9%81%D9%8A%20Git/%D9%84%D9%85%D8%A7%D8%B0%D8%A7%20%D9%86%D8%AD%D8%AA%D8%A7%D8%AC%20Git%3F.md)
  - [مفهوم أنظمة التحكم بالنسخ.](#github.com/mohammed-tu/Learn-Git/blob/main/%D9%85%D9%82%D8%AF%D9%85%D8%A9%20%D9%81%D9%8A%20Git/%D9%85%D9%81%D9%87%D9%88%D9%85%20%D8%A3%D9%86%D8%B8%D9%85%D8%A9%20%D8%A7%D9%84%D8%AA%D8%AD%D9%83%D9%85%20%D8%A8%D8%A7%D9%84%D9%86%D8%B3%D8%AE.md)
  - [أنواع أنظمة التحكم بالنسخ](#github.com/mohammed-tu/Learn-Git/blob/main/%D9%85%D9%82%D8%AF%D9%85%D8%A9%20%D9%81%D9%8A%20Git/%D8%A3%D9%86%D9%88%D8%A7%D8%B9%20%D8%A3%D9%86%D8%B8%D9%85%D8%A9%20%D8%A7%D9%84%D8%AA%D8%AD%D9%83%D9%85%20%D8%A8%D8%A7%D9%84%D9%86%D8%B3%D8%AE.md)
  - تحميل الأدوات
  - [تنزيل Git على Windows](#github.com/mohammed-tu/Learn-Git/blob/main/%D8%AA%D8%AD%D9%85%D9%8A%D9%84%20%D8%A7%D9%84%D8%A3%D8%AF%D9%88%D8%A7%D8%AA/%D8%AA%D9%86%D8%B2%D9%8A%D9%84%20Git%20%D8%B9%D9%84%D9%89%20Windows.md)
  - [تنزيل Git على macOS](#github.com/mohammed-tu/Learn-Git/blob/main/%D8%AA%D8%AD%D9%85%D9%8A%D9%84%20%D8%A7%D9%84%D8%A3%D8%AF%D9%88%D8%A7%D8%AA/%D8%AA%D9%86%D8%B2%D9%8A%D9%84%20Git%20%D8%B9%D9%84%D9%89%20macOS.md)
  - ابدأ مع Git
  - [الامر git init جزء1](#github.com/mohammed-tu/Learn-Git/blob/main/%D8%A7%D8%A8%D8%AF%D8%A3%20%D9%85%D8%B9%20Git/%D8%A7%D9%84%D8%A7%D9%85%D8%B1%20git%20init%20%D8%AC%D8%B2%D8%A11.md)
  - [الامر git init جزء2](#github.com/mohammed-tu/Learn-Git/blob/main/%D8%A7%D8%A8%D8%AF%D8%A3%20%D9%85%D8%B9%20Git/%D8%A7%D9%84%D8%A7%D9%85%D8%B1%20git%20init%20%D8%AC%D8%B2%D8%A12.md)
  - مراحل الملفات | git Stages
  - [مفهوم Git Stages](#github.com/mohammed-tu/Learn-Git/blob/main/%D9%85%D8%B1%D8%A7%D8%AD%D9%84%20%D8%A7%D9%84%D9%85%D9%84%D9%81%D8%A7%D8%AA%20%7C%20git%20Stages/%D9%85%D9%81%D9%87%D9%88%D9%85%20Git%20Stages.md)
  - [الامر git status](#github.com/mohammed-tu/Learn-Git/blob/main/%D9%85%D8%B1%D8%A7%D8%AD%D9%84%20%D8%A7%D9%84%D9%85%D9%84%D9%81%D8%A7%D8%AA%20%7C%20git%20Stages/%D8%A7%D9%84%D8%A7%D9%85%D8%B1%20git%20status.md)
  - [الأمر git add](#github.com/mohammed-tu/Learn-Git/blob/main/%D9%85%D8%B1%D8%A7%D8%AD%D9%84%20%D8%A7%D9%84%D9%85%D9%84%D9%81%D8%A7%D8%AA%20%7C%20git%20Stages/%D8%A7%D9%84%D8%A3%D9%85%D8%B1%20git%20add.md)
  - [تهيئة Git](#github.com/mohammed-tu/Learn-Git/blob/main/%D9%85%D8%B1%D8%A7%D8%AD%D9%84%20%D8%A7%D9%84%D9%85%D9%84%D9%81%D8%A7%D8%AA%20%7C%20git%20Stages/%D8%AA%D9%87%D9%8A%D8%A6%D8%A9%20Git.md)
  - [الامر git commit](#github.com/mohammed-tu/Learn-Git/blob/main/%D9%85%D8%B1%D8%A7%D8%AD%D9%84%20%D8%A7%D9%84%D9%85%D9%84%D9%81%D8%A7%D8%AA%20%7C%20git%20Stages/%D8%A7%D9%84%D8%A7%D9%85%D8%B1%20git%20commit.md)
  - [تحديث رسالة commit](#github.com/mohammed-tu/Learn-Git/blob/main/%D9%85%D8%B1%D8%A7%D8%AD%D9%84%20%D8%A7%D9%84%D9%85%D9%84%D9%81%D8%A7%D8%AA%20%7C%20git%20Stages/%D8%AA%D8%AD%D8%AF%D9%8A%D8%AB%20%D8%B1%D8%B3%D8%A7%D9%84%D8%A9%20commit.md)
  - [إعادة الملفات من مرحلة Staged](#github.com/mohammed-tu/Learn-Git/blob/main/%D9%85%D8%B1%D8%A7%D8%AD%D9%84%20%D8%A7%D9%84%D9%85%D9%84%D9%81%D8%A7%D8%AA%20%7C%20git%20Stages/%D8%A5%D8%B9%D8%A7%D8%AF%D8%A9%20%D8%A7%D9%84%D9%85%D9%84%D9%81%D8%A7%D8%AA%20%D9%85%D9%86%20%D9%85%D8%B1%D8%AD%D9%84%D8%A9%20Staged.md)
  - [إخفاء الملفات باستخدام gitignore](#github.com/mohammed-tu/Learn-Git/blob/main/%D9%85%D8%B1%D8%A7%D8%AD%D9%84%20%D8%A7%D9%84%D9%85%D9%84%D9%81%D8%A7%D8%AA%20%7C%20git%20Stages/%D8%A5%D8%AE%D9%81%D8%A7%D8%A1%20%D8%A7%D9%84%D9%85%D9%84%D9%81%D8%A7%D8%AA%20%D8%A8%D8%A7%D8%B3%D8%AA%D8%AE%D8%AF%D8%A7%D9%85%20gitignore.md)
  - استعراض تاريخ المشروع | Git log
  - [الامر git log](#github.com/mohammed-tu/Learn-Git/blob/main/%D8%A7%D8%B3%D8%AA%D8%B9%D8%B1%D8%A7%D8%B6%20%D8%AA%D8%A7%D8%B1%D9%8A%D8%AE%20%D8%A7%D9%84%D9%85%D8%B4%D8%B1%D9%88%D8%B9%20%7C%20Git%20log/%D8%A7%D9%84%D8%A7%D9%85%D8%B1%20git%20log.md)
  - [الامر git log --oneline](#github.com/mohammed-tu/Learn-Git/blob/main/%D8%A7%D8%B3%D8%AA%D8%B9%D8%B1%D8%A7%D8%B6%20%D8%AA%D8%A7%D8%B1%D9%8A%D8%AE%20%D8%A7%D9%84%D9%85%D8%B4%D8%B1%D9%88%D8%B9%20%7C%20Git%20log/%D8%A7%D9%84%D8%A7%D9%85%D8%B1%20git%20log%20--oneline.md)
  - الفروع | Git Branches
  - [مفهوم الفروع | Branches Concept](#github.com/mohammed-tu/Learn-Git/blob/main/%D8%A7%D9%84%D9%81%D8%B1%D9%88%D8%B9%20%7C%20Git%20Branches/%D9%85%D9%81%D9%87%D9%88%D9%85%20%D8%A7%D9%84%D9%81%D8%B1%D9%88%D8%B9%20%7C%20Branches%20Concept.md)
  - [إنشاء وعرض الفروع | git branch](#github.com/mohammed-tu/Learn-Git/blob/main/%D8%A7%D9%84%D9%81%D8%B1%D9%88%D8%B9%20%7C%20Git%20Branches/%D8%A5%D9%86%D8%B4%D8%A7%D8%A1%20%D9%88%D8%B9%D8%B1%D8%B6%20%D8%A7%D9%84%D9%81%D8%B1%D9%88%D8%B9%20%7C%20git%20branch.md)
  - [الانتقال بين الفروع | git checkout](#github.com/mohammed-tu/Learn-Git/blob/main/%D8%A7%D9%84%D9%81%D8%B1%D9%88%D8%B9%20%7C%20Git%20Branches/%D8%A7%D9%84%D8%A7%D9%86%D8%AA%D9%82%D8%A7%D9%84%20%D8%A8%D9%8A%D9%86%20%D8%A7%D9%84%D9%81%D8%B1%D9%88%D8%B9%20%7C%20git%20checkout.md)
  - [إنشاء فرع جديد والإنتقال له](#github.com/mohammed-tu/Learn-Git/blob/main/%D8%A7%D9%84%D9%81%D8%B1%D9%88%D8%B9%20%7C%20Git%20Branches/%D8%A5%D9%86%D8%B4%D8%A7%D8%A1%20%D9%81%D8%B1%D8%B9%20%D8%AC%D8%AF%D9%8A%D8%AF%20%D9%88%D8%A7%D9%84%D8%A5%D9%86%D8%AA%D9%82%D8%A7%D9%84%20%D9%84%D9%87.md)
  - [إعادة تسمية الفرع](#github.com/mohammed-tu/Learn-Git/blob/main/%D8%A7%D9%84%D9%81%D8%B1%D9%88%D8%B9%20%7C%20Git%20Branches/%D8%A5%D8%B9%D8%A7%D8%AF%D8%A9%20%D8%AA%D8%B3%D9%85%D9%8A%D8%A9%20%D8%A7%D9%84%D9%81%D8%B1%D8%B9.md)
  - [حذف الفرع](#github.com/mohammed-tu/Learn-Git/blob/main/%D8%A7%D9%84%D9%81%D8%B1%D9%88%D8%B9%20%7C%20Git%20Branches/%D8%AD%D8%B0%D9%81%20%D8%A7%D9%84%D9%81%D8%B1%D8%B9.md)
  - الدمج | Merge
  - [مفهوم الدمج | Merge](#github.com/mohammed-tu/Learn-Git/blob/main/%D8%A7%D9%84%D8%AF%D9%85%D8%AC%20%7C%20Merge/%D9%85%D9%81%D9%87%D9%88%D9%85%20%D8%A7%D9%84%D8%AF%D9%85%D8%AC%20%7C%20Merge.md)
  - [الدمج المباشر | Fast-Forward Merge](#github.com/mohammed-tu/Learn-Git/blob/main/%D8%A7%D9%84%D8%AF%D9%85%D8%AC%20%7C%20Merge/%D8%A7%D9%84%D8%AF%D9%85%D8%AC%20%D8%A7%D9%84%D9%85%D8%A8%D8%A7%D8%B4%D8%B1%20%7C%20Fast-Forward%20Merge.md)
  - [الدمج الحقيقي | True Merge](#github.com/mohammed-tu/Learn-Git/blob/main/%D8%A7%D9%84%D8%AF%D9%85%D8%AC%20%7C%20Merge/%D8%A7%D9%84%D8%AF%D9%85%D8%AC%20%D8%A7%D9%84%D8%AD%D9%82%D9%8A%D9%82%D9%8A%20%7C%20True%20Merge.md)
  - العلامات | Tags
  - [إنشاء وعرض tag](#github.com/mohammed-tu/Learn-Git/blob/main/%D8%A7%D9%84%D8%B9%D9%84%D8%A7%D9%85%D8%A7%D8%AA%20%7C%20Tags/%D8%A5%D9%86%D8%B4%D8%A7%D8%A1%20%D9%88%D8%B9%D8%B1%D8%B6%20tag.md)
  - [عرض تفاصيل tag](#github.com/mohammed-tu/Learn-Git/blob/main/%D8%A7%D9%84%D8%B9%D9%84%D8%A7%D9%85%D8%A7%D8%AA%20%7C%20Tags/%D8%B9%D8%B1%D8%B6%20%D8%AA%D9%81%D8%A7%D8%B5%D9%8A%D9%84%20tag.md)
  - [حذف tag](#github.com/mohammed-tu/Learn-Git/blob/main/%D8%A7%D9%84%D8%B9%D9%84%D8%A7%D9%85%D8%A7%D8%AA%20%7C%20Tags/%D8%AD%D8%B0%D9%81%20tag.md)
  - استنساخ مشروع | Git Cloning
  - [الأمر git clone](#github.com/mohammed-tu/Learn-Git/blob/main/%D8%A7%D8%B3%D8%AA%D9%86%D8%B3%D8%A7%D8%AE%20%D9%85%D8%B4%D8%B1%D9%88%D8%B9%20%7C%20Git%20Cloning/%D8%A7%D9%84%D8%A3%D9%85%D8%B1%20git%20clone.md)
  - [الأمر git push](#github.com/mohammed-tu/Learn-Git/blob/main/%D8%A7%D8%B3%D8%AA%D9%86%D8%B3%D8%A7%D8%AE%20%D9%85%D8%B4%D8%B1%D9%88%D8%B9%20%7C%20Git%20Cloning/%D8%A7%D9%84%D8%A3%D9%85%D8%B1%20git%20push.md)
  - [الأمر git pull](#github.com/mohammed-tu/Learn-Git/blob/main/%D8%A7%D8%B3%D8%AA%D9%86%D8%B3%D8%A7%D8%AE%20%D9%85%D8%B4%D8%B1%D9%88%D8%B9%20%7C%20Git%20Cloning/%D8%A7%D9%84%D8%A3%D9%85%D8%B1%20git%20pull.md)
  - المشاريع الخارجية | Remote
  - [إضافة remote](#github.com/mohammed-tu/Learn-Git/blob/main/%D8%A7%D9%84%D9%85%D8%B4%D8%A7%D8%B1%D9%8A%D8%B9%20%D8%A7%D9%84%D8%AE%D8%A7%D8%B1%D8%AC%D9%8A%D8%A9%20%7C%20Remote/%D8%A5%D8%B6%D8%A7%D9%81%D8%A9%20remote.md)
  - [رفع التحديثات لمشروع خارجي](#github.com/mohammed-tu/Learn-Git/blob/main/%D8%A7%D9%84%D9%85%D8%B4%D8%A7%D8%B1%D9%8A%D8%B9%20%D8%A7%D9%84%D8%AE%D8%A7%D8%B1%D8%AC%D9%8A%D8%A9%20%7C%20Remote/%D8%B1%D9%81%D8%B9%20%D8%A7%D9%84%D8%AA%D8%AD%D8%AF%D9%8A%D8%AB%D8%A7%D8%AA%20%D9%84%D9%85%D8%B4%D8%B1%D9%88%D8%B9%20%D8%AE%D8%A7%D8%B1%D8%AC%D9%8A.md)
  - [حذف remote](#github.com/mohammed-tu/Learn-Git/blob/main/%D8%A7%D9%84%D9%85%D8%B4%D8%A7%D8%B1%D9%8A%D8%B9%20%D8%A7%D9%84%D8%AE%D8%A7%D8%B1%D8%AC%D9%8A%D8%A9%20%7C%20Remote/%D8%AD%D8%B0%D9%81%20remote.md)

****
 ####  المتدرب محمد الحربي
 #### بإشراف لمياء القحطاني 
 #### من مجموعة طويق


