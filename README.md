# Test-Django  
Описание  
Это небольшое Django-приложение, состоящее из двух частей:  

API для продуктов: создание и получение списка продуктов.  
HTML + JavaScript: интерфейс для взаимодействия с API (добавление продуктов и отображение списка).  
Функционал  
API:  
POST /api/products/ — создание продукта (название, описание, цена).  
GET /api/products/ — получение списка всех продуктов в формате JSON.  
Фронтенд:  
Форма для добавления нового продукта.  
Таблица для отображения всех продуктов на странице.  

Запустить можно 2-мя способами:
1) Локально  
pip install -r requirements.txt  
python manage.py migrate  
python manage.py runserver  
2) с помощью Docker
docker build -t django-products-api .
docker run -p 8000:8000 django-products-api

О себе  
Я заинтересован в интересной и долгосрочной работе с Django и фронтенд-технологиями. Готов к познанию большого количества новой информации и открытии для себя нового.

Контакты:  
Email: andrey.ageev.04@gmail.com
Телефон: 89253032206
Telegram: @AndreyAgEEvf