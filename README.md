 ![](https://github.com/MohammedAlsubhi/lolcat/blob/master/ass/4152-2.gif?raw=true)


## Installation التنصيب

كيفية تثبيت حزمة"figlet"

sudo apt-get install figlet

git clone https://github.com/MohammedAlsubhi/lolcat.git

 ولا ننسي حزم او بكجات الجيم
 
 # gem install lolcat 
 
 
 
 
 Kali Linux 
 هذه الاداة سطر من الاوامر لإخراج قوس قزح من الالوان في بيئة الكالي لنكس 
 
 لو ضغطنا الامر 
 
 # lolcat -h
 راح تجينا هالصوره بالوان مزخرفة زي مانتم شايفين
 
 وبشكل ممتع ومبهج
 
 ![](https://github.com/MohammedAlsubhi/lolcat/blob/master/ass/screenshot.png)
 
 
 
علي سبيل المثال


 لو كتبنا بالترمنل


ونستعرض الملفات في اي مكان راح نستخدم الامر


# Ls

# ls | lolcat
================


![](https://github.com/MohammedAlsubhi/lolcat/blob/master/ass/lolcat.PNG?raw=true)

اتمني الجميع يطبق معايه وكل واحد يشوف الالوان علي اسماء المجلدات كيف اصبحت   جدا مبهجة وممتعة



 لو حبينا نستعلم عن التاريخ بالوان قوس قزح المفرحة
 
 # date | lolcat
 
 كل ما نستخدم الامر كل مره يعطينا لون جديد
 
![](https://github.com/MohammedAlsubhi/lolcat/blob/master/ass/date.PNG?raw=true)

وكذاللك  التقويم

# cal | lolcat


![](https://github.com/MohammedAlsubhi/lolcat/blob/master/ass/cal.PNG?raw=true)


فرضا انشئنا ملف قابل للقرائه بصيغه تكست على سطح المكتب 
ونريد قراءه الملف بالوان زاهيه 
اذهب الي مسار الملف

ونفترض اسم الملف

1.txt

فسنكتب

# lolcat 1.txt


 ونستطيع ايضا أن نطبع اي كلمه في الترمن بالعربي انجليزي اي لغه تنسخهاوتلصقها مهما كانت


# echo I ❤ Mr_Robot | lolcat

![](https://github.com/MohammedAlsubhi/lolcat/blob/master/ass/shiny.gif?raw=true)

 
 ولو حبينا نكبر الاحرف بشكل اعتيادي ونجعل المخرجات ايضا ملونه بالوان زاهية كما تعودنا
 
 راح نقول
 
 # figlet I Love Mr.Robot | lolcat
 
 
 ![](https://github.com/MohammedAlsubhi/lolcat/blob/master/ass/figlet.gif?raw=true)

لكن في حاله تريد ان يتلئلئ النص 500 مره او 10000 مره 

فعليك كتابة هذا الامر معي


# echo I ❤ Mr_Robot | lolcat -a -d 500

echo بمعني اطبع 

500 هنا عدد المرات

-a -d هذه رموز الاوان المستخدمه وقابله للزياده او التغير

 ![](https://github.com/MohammedAlsubhi/lolcat/blob/master/ass/shainy.PNG?raw=true)
 
 

الان سندمج امرين معا
 سندمج امر تكبير الخط والتلئلئ
 
 شاهد
 

# figlet I Love Mr.Robot |  lolcat -a -d 15

15 عدد الثواني او المرات

سيصبح



 ![](https://github.com/MohammedAlsubhi/lolcat/blob/master/ass/i%20love%20mr%20robot.gif?raw=true)



جميل
لو نحب نستعرض الخطوط ونختار منها خط 
نجرب هذا الامر

# showfigfonts 

 ![](https://github.com/MohammedAlsubhi/lolcat/blob/master/ass/showfigfonts.gif?raw=true)

# نقطه جديدة
# سنتكلم الان عن تغير الاسم في الترمنل واضافه الوان لها

# NANO نانو 
نانو محرر صغير ومحبوب جدا. ينسخ الشكل والمظهر هو برنامج او سكربت  مجاني ، وينفذ العديد من 

الميزات 

، مثل: فتح ملفات متعددة ، والتمرير في كل سطر ، والتراجع / الإعادة ، وتلوين بناء الجملة ، وترقيم الأسطر ، وخطوط

كما تعودنا ننزل البكجات والحزم حقت الخطوط


# sudo apt-get install figlet

وندخل علي مجلد Etc


# cd /etc

 ونستعرض الملفات
 
 # ls
 
 ونبحث عن ملف باسم:
 
bash.bashrc

ننسخ الاسم 
 ونكتب امر
 # nano bash.bashrc
 
 
 ![](https://github.com/MohammedAlsubhi/lolcat/blob/master/ass/tryag.gif?raw=true)
 
 
