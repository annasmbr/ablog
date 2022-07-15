Django Blog
Full-Featured Blog with Django web framework.
Clone project & Install Requirements
Make sure you have already installed python3 and git.

$ git clone https://github.com/annasmbr/ablog.git && cd django-blog
$ pip install -r requirements.txt
Migrate & Collect Static
$ cd src && python manage.py migrate
$ python manage.py collectstatic
Create Admin User
$ python manage.py createsuperuser
Run Server
$ python manage.py runserver
Enter your browser http://localhost:8000/. You can login via admin in http://localhost:8000/admin/.