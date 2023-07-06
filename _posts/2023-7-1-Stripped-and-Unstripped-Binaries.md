---
layout: post
status: publish
published: true
title: Stripped and Unstripped Binaries 
author: horus
categories: [Binary_Exploitation]
tags: [Binary_Exploitation , Arabic]
comments: true
image: 0x00.png
lang: ar
--- 

###     …  بِسْمِ اللَّـهِ الرَّحْمَـٰنِ الرَّحِيمِ  …


## المقدمة :
 في هذه السلسة بأذن الله سنشرح الBinary Exploitation techniques and Basics باللغة العربية قدر المستطاع لأثراء المحتوى العربي في مجال الامن السيبراني و سنبدأ اول مقال بشرح الفرق بين ال  stripped binary و ال unstripped binary و كيف نجد الmain function في الunstripped binaries 


---
### Stripped Vs Unstripped : 
تنقسم انواع الbinaries الى نوعان stripped و unstripped  . الunstripped binary هو عند تحويل الكود الي binary بطريقة الcompile العادية عن طريق هذا الامر مثلا `gcc code.c -o code` . اما عن الstripped binary هي عند تحويل الكود الي binary لكن بحذف الdebugging information لاخفاء اسامي الfunctions و تصعيب المهمة علي الreverse engineers و ايضا تخفيف 