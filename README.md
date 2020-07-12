
## Örnek Django blog site 

Bu django site öreneğini "barissaslan" adlı kullanıcının eğitimini izleyerek, kullanılan araçların son versiyonlarını kullanarak yaptım.

### Kurulum
İndirdikten sonra proje dizini içerisinde:


`virtualenv venv .` "Nokta" bulunan konuma kurması için.

Linux & Mac: `source venv/bin/activate`

Windows: `venv\Scripts\activate`

`pip install -r requirements.txt`

`python manage.py makemigrations`

`python manage.py migrate`

`python manage.py createsuper *name`

`python manage.py runserver`
