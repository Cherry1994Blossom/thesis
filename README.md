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
<p dir="rtl" align="right">
اومدم اوبونتو 18.4 نصب کردم
</br>
بعد توی مسیرroofs/home فایل های data , jingwei رو اضاف کردم
</br>
مسیر هاشون رو به start.sh اضاف کردم
</p>
<p>
permission denied ....
</br>
chmod +x *
</p><p dir="rtl" align="right">
مشکل رفع شد
</br>
خواستم دستور زیر رو اجرا کنم ک خطا گرفتم 
</p><p>
sudo apt install python-pip
</br>
E:Unable to locate package python-pip</p><p dir="rtl" align="right">
مراحل زیر رو انجام دادم که خطا رفع بشه :
</p><p>sudo nano /etc/apt/sources.list
</br>Press Ctrl+O to save the file
</br>sudo apt update
</br>sudo apt install python-pip
</p><p dir="rtl" align="right">
وسطش پرسید(Y/n)و منY رو زدم تا نصب تموم بشه
</br>
دستور زیر رو زدم
</p><p>
pip install jupyter
 </br>
 sudo apt install jupyter-core
</p><p dir="rtl" align="right">
  همه اینارو زدم ولی اشتباه بود با دستور زیر درست شد:
</p>
<p>
Ubuntu 18.04 :
</br>
sudo apt install python3-notebook jupyter jupyter-core python-ipykernel  
</br>
To start the notebook server run the following command:
</br>
jupyter notebook
</p>
