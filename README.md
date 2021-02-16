# hello_django
### Iniciando meu projeto Django

```sh

--django-admin startproject mysite
--cd mysite
--python manage.py migrate --run-syncdb
--python manage.py startapp core
--python manage.py runserver

-- setings.py > INSTALLED_APPS > core
-- urls.py > from core import views
-- urls.py > urlpatterns > path('', views.home, name='home')

```