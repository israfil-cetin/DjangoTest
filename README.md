
## Örnek Django blog site 

Bu django site öreneğini "barissaslan" adlı kullanıcının eğitimini izleyerek, kullanılan araçların son versiyonlarını kullanarak yaptım.

### Kurulum
İndirdikten sonra proje dizini içerisinde:


`virtualenv venv`

Linux & Mac: `source venv/bin/activate`

Windows: `venv\Scripts\activate`

`pip install -r requirements.txt`

`python manage.py makemigrations`

`python manage.py migrate`

`python manage.py createsuperuser *name`

`python manage.py runserver`
