# Ob-havo

Ob-havo - bu ob-havo ma'lumotlarini olish va prognoz qilish uchun RESTful API.

## Loyiha haqida
Ushbu loyiha turli joylashuvlar uchun ob-havo ma'lumotlarini saqlash, prognozlarni chiqarish va tahliliy statistikalarni olish imkonini beradi.

## Texnologiyalar
Loyihada quyidagi texnologiyalar ishlatilgan:
- Python 3.12
- Django Rest Framework (DRF)
- SQLite3

## API Endpointlar

### Locations (Joylar):
- `GET http://127.0.0.1:8000/api/locations/` - Barcha joylar ro‘yxati
- `POST http://127.0.0.1:8000/api/locations/` - Yangi joy qo‘shish
- `GET http://127.0.0.1:8000/api/locations/{id}/` - Aniq joy ma’lumotlari
- `PUT http://127.0.0.1:8000/api/locations/{id}/` - Joy ma’lumotlarini yangilash
- `DELETE http://127.0.0.1:8000/api/locations/{id}/` - Joyni o‘chirish

### WeatherData (Ob-havo ma’lumotlari):
- `GET http://127.0.0.1:8000/api/weather-data/` - Barcha ob-havo ma’lumotlari
- `POST http://127.0.0.1:8000/api/weather-data/` - Yangi ob-havo ma’lumoti qo‘shish
- `GET http://127.0.0.1:8000/api/weather-data/{id}/` - Aniq ob-havo ma’lumoti
- `PUT http://127.0.0.1:8000/api/weather-data/{id}/` - Ob-havo ma’lumotini yangilash
- `DELETE http://127.0.0.1:8000/api/weather-data/{id}/` - Ob-havo ma’lumotini o‘chirish
- `GET http://127.0.0.1:8000/api/weather-data/location/{location_id}/` - Ma’lum joy uchun ob-havo ma’lumotlari

### Forecasts (Prognozlar):
- `GET http://127.0.0.1:8000/api/forecasts/` - Barcha prognozlar
- `POST http://127.0.0.1:8000/api/forecasts/` - Yangi prognoz qo‘shish
- `GET http://127.0.0.1:8000/api/forecasts/{id}/` - Aniq prognoz ma’lumotlari
- `PUT http://127.0.0.1:8000/api/forecasts/{id}/` - Prognozni yangilash
- `DELETE http://127.0.0.1:8000/api/forecasts/{id}/` - Prognozni o‘chirish
- `GET http://127.0.0.1:8000/api/forecasts/location/{location_id}/` - Ma’lum joy uchun prognozlar

### Analytics (Tahlillar):
- `GET http://127.0.0.1:8000/api/analytics/temperature-avg/` - O‘rtacha harorat (barcha joylar bo‘yicha)
- `GET http://127.0.0.1:8000/api/analytics/precipitation-sum/` - Umumiy yog‘ingarchilik miqdori
- `GET http://127.0.0.1:8000/api/analytics/wind-speed-max/` - Maksimal shamol tezligi

## O'rnatish va Ishga tushirish

1. Loyihani klonlash:
   ```bash
   git clone https://github.com/username/ob-havo.git
   cd ob-havo
   ```

2. Virtual muhit yaratish va faollashtirish:
   ```bash
   python -m venv venv
   source venv/bin/activate  
   ```

3. Kerakli kutubxonalarni o‘rnatish:
   ```bash
   pip install -r requirements.txt
   ```

4. Ma'lumotlar bazasini yaratish:
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

5. Serverni ishga tushirish:
   ```bash
   python manage.py runserver
   ```

Endi API `http://127.0.0.1:8000/` manzilida ishlaydi.

## Muallif
# Damirbek Rustambekov

# GitHub Profilingiz
- [GitHub Profilingiz](https://github.com/damirrustambek0v)




