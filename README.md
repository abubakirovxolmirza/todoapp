# todo app
A simple todo app built with django

![todo App](https://github.com/abubakirovxolmirza/todoapp/blob/main/staticfiles/todoApp.png)
### O'rnatish
Ushbu loyihani o'rnatish uchun terminalga kerakli buyruqni kirgaz
```bash
$ git clone https://github.com/abubakirovxolmirza/todoapp.git
```
Ushbu ilovani ishga tushirish uchun kompyuteringizga django o'rnatilishi kerak bo'ladi. Yuklab olish qoʻllanmasi uchun https://www.djangoproject.com/download/ saytiga oʻting

Django-ni yuklab olganingizdan so'ng, o'tkazilgan fayl katalogiga o'ting va quyidagi buyruqni bajaring
```bash
$ python manage.py makemigrations
```

Bu ushbu ilovani ishga tushirish uchun zarur bo'lgan barcha migratsiya faylini (ma'lumotlar bazasi ko'chishi) yaratadi.

Endi ushbu migratsiyalarni qo'llash uchun quyidagi buyruqni bajaring
```bash
$ python manage.py migrate
```

Oxirgi qadam, so'ngra bizning vazifamiz ilovasi jonli bo'ladi. Ushbu ilovani ishga tushirish uchun administrator foydalanuvchi yaratishimiz kerak. Terminalda quyidagi buyruqni kiriting va administrator foydalanuvchi uchun foydalanuvchi nomi, parol va elektron pochta manzilini kiriting```bash
$ python manage.py createsuperuser
```

Biz serverni hozir ishga tushirishimiz kerak, shundan so'ng biz todoapp  ilovasidan foydalanishni boshlashimiz mumkin. Quyidagi buyruq bilan serverni ishga tushiring

```bash
$ python manage.py runserver
```

Server joylashtirilgandan so'ng, ilova uchun http://127.0.0.1:8000/todos manziliga o'ting.

Hayr salomat bo'ling
