**خطوات إنشاء مشروع فايربيس جديد وربطه بتطبيق الاندرويد**

1- الدخول للرابط التالي: https://firebase.google.com/ </br>
2- الضغط على **GET STARTED** </br>
3- قم بإنشاء مشروع جديد بالضغط على **Add project** </br>
![screenshot from 2018-01-07 12-12-18](https://user-images.githubusercontent.com/35188729/34649468-028f5d36-f3c1-11e7-8237-07dc4fe96971.png)

4- قم بإدخال اسم المشروع الخاص بك في خانة **Project Name** </br>
5- اختيار الدولة من قائمة **Country/region** </br>
6- الضغط على **CREATE PROJECT** </br>
![screenshot from 2018-01-07 12-12-59 1](https://user-images.githubusercontent.com/35188729/34649477-3b497a08-f3c1-11e7-8aa0-dd4fdafc79e1.png)

#### بهذه الخطوات نكون قد أنشأنا مشروع</br> Firebase بنجاح</br>
#### والآن لربط المشروع بتطبيق الاندرويد نقوم باتباع الخطوات التالية: </br>

7- الضغط على **Add Firebase to your Android app** </br>
![screenshot from 2018-01-07 12-24-56](https://user-images.githubusercontent.com/35188729/34649566-b1c64c50-f3c2-11e7-8d71-e154dcd21554.png)

8- قم بنسخ اسم الباكج من ملف المانيفست بالاندرويد ثم إدخاله في خانة **Android package name** </br>
9- الضغط على **REGISTER APP**
![screenshot from 2018-01-07 12-31-23](https://user-images.githubusercontent.com/35188729/34649571-f0c21952-f3c2-11e7-8c8b-1245287dd3fe.png)

10- قم بتحميل ملف **json** </br>
بالضغط على **Download google-services.json** </br>

11- العودة للتطبيق في الاندرويد ستوديو ثم نسخ الملف **json** </br>
ضمن الملفات الخاصة بالتطبيق
![screenshot from 2018-01-07 12-49-52](https://user-images.githubusercontent.com/35188729/34650287-c35ecfac-f3cf-11e7-88f1-dbc4e0a836b3.png)

12- في الاندرويد ستوديو قم بفتح الملف **build.gradle**</br> على مستوى المشروع بشكل كامل ثم قم بنسخ هذا الأمر كما هو موضع في الصورة</br>  **classpath 'com.google.gms:google-services:3.1.0'**
![screenshot from 2018-01-07 17-42-51](https://user-images.githubusercontent.com/35188729/34650445-7c8ae112-f3d2-11e7-9140-65c6c27a3270.png)

12- في الاندرويد ستوديو قم بفتح الملف **build.gradle**</br> على مستوى التطبيق ثم قم بنسخ هذا الأمر كما هو موضع في الصورة</br>  **apply plugin: 'com.google.gms.google-services'**

![screenshot from 2018-01-07 17-42-37](https://user-images.githubusercontent.com/35188729/34650443-731fc106-f3d2-11e7-957b-777dedaab532.png)


