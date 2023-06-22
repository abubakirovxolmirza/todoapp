# todo app
A simple todo app built with django

![todo App](https://raw.githubusercontent.com/shreys7/django-todo/develop/staticfiles/todoApp.png)
### O'rnatish
Ushbu loyihani o'rnatish uchun terminalga kerakli buyruqni kirgaz
```bash
$ git clone https://github.com/shreys7/django-todo.git
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

That was pretty simple, right? Now let's make the App live. We just need to start the server now and then we can start using our simple todo App. Start the server by following command

```bash
$ python manage.py runserver
```

Server joylashtirilgandan so'ng, ilova uchun http://127.0.0.1:8000/todos manziliga o'ting.

Hayr salomat bo'ling