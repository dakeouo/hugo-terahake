---
author: "Dake Hong"
title: "遇見硬體描述語言"
description: "可編程矽智財設計(Verilog)"
date: 2019-10-11T12:18:12+08:00
tags: [
    "舊文重發",
    "心得文",
]
---
在大一的時候，我們在必修的數位課程學過了CPLD/VHDL，透過VHDL讓我們知道在之前高中高職在數位邏輯所學的邏輯閘、加法器、正反器、多工器等電路，在實體的硬體上面是如何去實現，得知霹靂燈、倒數計時器、電子時鐘、跑馬燈、小綠人是如何利用程式+硬體的方式被製作出來。
<!--more-->
到了大二之後，就有Verilog、SOPC的選修課程可以選。但是你一定想問，到底VHDL、Verilog和SOPC到底差在哪裡？答案是其實沒甚麼差別，只是寫法不同而已。就跟當你要寫一隻程式的時候，你可以用C語言寫、可以用Java寫，也可以用Python寫，甚至你要用組合語言寫也可以，不管你有甚麼程式語言呈現，其實它們到最後呈現出來的結果是一樣的。

不過如果你要學習硬體描述語言的話，還是從VHDL開始學起較佳，因為它程式比較直觀，初學者比較容易理解，可讀性較高。至於Verilog的話，我覺得它比較接近機器語言，但又沒有到組合語言那麼低階，不過越接近機器語言的程式語言，你寫起來就越覺得"傲嬌"。至於SOPC的話，簡單來說，就是用C語言去寫硬體，最我認證的硬體描述語言中，它算最高階的了，所以如果你要學習寫SOPC的話，應該要先有C語言的基礎，再來寫SOPC會比較好。

不過我發現，現在念資工系的學生，似乎比較少人想要碰硬體，對硬體很排斥，覺得外來只要朝軟體方面發展就行了。不過其實硬體方面的工作也是很有賺頭的，甚至所謂的"韌體"(硬體+軟體)才是現今企業很需要的人才。所以呢，大家好好朝向韌體人才的路邁進吧!