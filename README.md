<p dir="rtl" align="right">
اومدم پایتون 2.7 نصب کردم
<br/>
دسترسیpipو پایتون به ویندوز دادم
<br/>
بعد ژوپیترنصب کردم 
<br/>
توی کامنت cmdکدهارو اجرا کردم ولی جواب نداد
<br/>
همه ی فایل هارو بردم توی فایل baselines
<br/>
بسته های مورد نیاز رو با دستور 
</p>
<br/>
<p>
pip install...
</p><br/>
<p dir="rtl" align="right">
نصب کردم که خطای
</p>
<br/>
<p>
 cannot import name ROOT_PATH
</p>
<p dir="rtl" align="right">
میداد اومدم کالی لینوکس نصب کردم
<br/>
با دستورات زیر مسیرم رو پیدا کردم ولی بازم خطا گرفتم !!!!!!
</p>
<br/>
<p>
alibani@alibani-PC:~$ ls
</br>
alibani@alibani-PC:~$ su -
</br>
Password:*********
</br>
root@alibani-PC:~# cd jingwei
</br>
root@alibani-PC:~/jingwei# cd jingwei-master
</br>
root@alibani-PC:~/jingwei/jingwei-master# ls
</br>
LICENSE    __init__.py  code-framework.png  image_features  setup.sh   start.sh
</br>
README.md  baselines    doit                model_based     start.bat
</br>
root@alibani-PC:~/jingwei/jingwei-master# python usertags.py
</br>
python: can't open file 'usertags.py': [Errno 2] No such file or directory
</br>
root@alibani-PC:~/jingwei/jingwei-master# cd baselines
</br>
root@alibani-PC:~/jingwei/jingwei-master/baselines# python usertags.py
</br>
Traceback (most recent call last):
</br>
  File "usertags.py", line 9, in <module>
 </br>
    from basic.common import ROOT_PATH, checkToSkip, niceNumber, printStatus, makedirsforfile
    </br>
ImportError: cannot import name ROOT_PATH
</br>
root@alibani-PC:~/jingwei/jingwei-master/baselines#
</p>





