# Customer-registration
برنامه ای برای ثبت مشتری ها در سایت یا فروشگاه
به علت حجم زیاد این پروژه اون رو در گوگل درایو قرار دادم در این لینک زیر میتونید پروژه رو نگاه کنید 
https://drive.google.com/file/d/1ibrZBa7WkPLnGC1X4Uoy4FZ27E9gOhzt/view?usp=sharing

# 🧾 پروژه ثبت مشتری فروشگاه با Django

این پروژه یک سیستم ساده و کاربردی برای ثبت، نمایش، و مدیریت مشتریان فروشگاه است که با استفاده از فریم‌ورک Django توسعه داده شده. طراحی پروژه به‌صورت ایزوله و ماژولار انجام شده و شامل فرم‌های ثبت، لیست مشتریان، و صفحات HTML اختصاصی است.

---

## 🛠️ تکنولوژی‌های استفاده‌شده

- Python (با پکیج‌های Tkinter و Django)
- Django 4.x
- SQLite3 (پایگاه داده پیش‌فرض)
- HTML (قالب‌های سفارشی با استفاده از `templates`)
- فرم‌های Django (`forms.py`)
- مدیریت مدل‌ها و پنل ادمین (`admin.py`)

---

## 📁 ساختار پروژه

  -py&django/
  -   ├── customer_project/ 
  -   │ ├── db.sqlite3 
  -   │ ├── manage.py 
  -   │ └── customer_project/ 
  -   │ ├── init.py │ 
   -  ├── asgi.py │ 
   -  ├── settings.py 
   -  │ ├── urls.py 
   -  │ └── wsgi.py 
   -  │ ├── customers/ 
   -  │ ├── init.py │ 
   -  ├── admin.py │ 
   -  ├── apps.py │ 
   -  ├── forms.py │ 
   -  ├── models.py │ 
   -  ├── tests.py │ 
   -  ├── urls.py │ 
   -  ├── views.py │ 
   -  ├── migrations/ 
   -  │ ├── templates/ 
   -  │ │ ├── home.html 
   -  │ │ ├── list.html 
   -  │ │ └── register.html

---

## 🎯 قابلیت‌های پروژه

- فرم ثبت مشتری با اعتبارسنجی
- نمایش لیست مشتریان ثبت‌شده
- قالب‌های HTML سفارشی برای صفحات مختلف
- مدیریت مدل‌ها از طریق پنل ادمین Django
- ساختار ایزوله برای توسعه‌پذیری بهتر

---

## 🚀 نحوه اجرا

۱. نصب پکیج‌های مورد نیاز (در محیط مجازی):

```bash
pip install django
python manage.py runserver
http://127.0.0.1:8000/
