<p dir="rtl" align="right">
اومدم پایتون 2.7 نصب کردم
<br/>
دسترسیpipو پایتون به ویندوز داادم
<br/>
بعد ژوپیترنصب کردم 
<br/>
توی کامنت cmdکدهارو اجرا کردم ولی جواب نداد
<br/>
همه ی فایل هارو بردم توی فایل baselines
<br/>
بسته های مورد نیاز رو با دستور 
<br/>
pip install...
<br/>
نصب کردم
<br/>
خطای
<br/>
 cannot import name ROOT_PATH
<br/>
میداد اومدم کالی لینوکس نصب کردم
<br/>
با دستورات زیر مسیرم رو پیدا کردم ولی بازم خطا گرفتم !!!!!!
</br>
alibani@alibani-PC:~$ ls
alibani@alibani-PC:~$ su -
Password:*********
root@alibani-PC:~# cd jingwei
root@alibani-PC:~/jingwei# cd jingwei-master
root@alibani-PC:~/jingwei/jingwei-master# ls
LICENSE    __init__.py  code-framework.png  image_features  setup.sh   start.sh
README.md  baselines    doit                model_based     start.bat
root@alibani-PC:~/jingwei/jingwei-master# python usertags.py
python: can't open file 'usertags.py': [Errno 2] No such file or directory
root@alibani-PC:~/jingwei/jingwei-master# cd baselines
root@alibani-PC:~/jingwei/jingwei-master/baselines# python usertags.py
Traceback (most recent call last):
  File "usertags.py", line 9, in <module>
    from basic.common import ROOT_PATH, checkToSkip, niceNumber, printStatus, makedirsforfile
ImportError: cannot import name ROOT_PATH
root@alibani-PC:~/jingwei/jingwei-master/baselines#
</p>





