Ob-havo 🌦️
Bu loyiha ob-havo ma'lumotlarini saqlash va boshqarish uchun ishlab chiqilgan Django veb-ilovasi. Loyiha orqali ob-havo prognozlari, tahlillar, va statistikalar o'rganish imkoniyati mavjud.

📋 Mundarija
Texnologiyalar
O'rnatish
Loyihani klonlash
Virtual muhitni yaratish
Virtual muhitni faollashtirish
Talab qilingan kutubxonalarni o'rnatish
Ma'lumotlar bazasini yaratish
Admin panelga kirish uchun superuser yaratish
Serverni ishga tushirish
Foydalanish
Analytics (Tahlillar)
Loyiha Tuzilmasi
Loyiha Asoschisi
🛠️ Texnologiyalar
Python 3.x
Django
SQLite (yoki boshqa ma'lumotlar bazasi)
Bootstrap (Frontend uchun)
JavaScript (Analytics uchun)
🚀 O'rnatish
1. Loyihani klonlash
Loyihani o'zingizning kompyuteringizga klonlash uchun quyidagi buyruqni ishlating:

bash
Копировать
git clone https://github.com/damirrustambek0v/ob-havo.git 
2. Virtual muhitni yaratish
Django loyihasini izolyatsiyalash uchun virtual muhit yaratish:

bash
Копировать
python -m venv venv
3. Virtual muhitni faollashtirish
Windows:
bash
Копировать
venv\Scripts\activate
macOS/Linux:
bash
Копировать
source venv/bin/activate
4. Talab qilingan kutubxonalarni o'rnatish
Loyihada ishlatadigan barcha kutubxonalarni o'rnatish uchun:

bash
Копировать
pip install -r requirements.txt
5. Ma'lumotlar bazasini yaratish
Django ma'lumotlar bazasini yaratish uchun:

bash
Копировать
python manage.py migrate
6. Admin panelga kirish uchun superuser yaratish
Admin panelga kirish uchun superuser yaratish:

bash
Копировать
python manage.py createsuperuser
Superuser yaratishda foydalanuvchi nomi, email va parolni kiritishingiz kerak.

7. Serverni ishga tushirish
Loyihani ishga tushirish uchun:

bash
Копировать
python manage.py runserver
Brauzeringizda http://127.0.0.1:8000/ manziliga o'ting.

🖥️ Foydalanish
Admin paneli: http://127.0.0.1:8000/admin/ manzilida mavjud. Superuser sifatida kirib, ob-havo ma'lumotlarini boshqarishingiz mumkin.
Analytics (Tahlillar): Ob-havo tahlillari va statistikalarini ko'rish uchun maxsus sahifa mavjud.
🖥️ Analytics (Tahlillar)
Loyihada ob-havo tahlil qilish imkoniyatlari mavjud. Bu bo'limda foydalanuvchilar ob-havo prognozlari va statistikalarini ko'rib chiqishlari mumkin.

Ob-havo Loyiha Tuzilmasi 📁
bash
Копировать
ob_havo/
├── manage.py
├── ob_havo/  # Django app
│   ├── migrations/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── views.py
│   └── ...
├── requirements.txt
└── ...
🖥️ Loyiha asoschisi
Asoschi: [Ismingiz yoki Username]

Loyihaning barcha kodlari va hujjatlari open-source bo'lib, siz o'zingizning ehtiyojlaringizga moslab tahrir qilishingiz mumkin.

Bu README fayli yordamida Django ob-havo loyihasini o'rnatish va undan foydalanish haqida to'liq ma'lumot olishingiz mumkin.

By Rustambekov D

