# DJANGO BASLANGIC

## Django Kurma

pip install django

## Django Proje Başlatma

django-admin startproject ProjeIsmi

## Test için Proje Çalıştırma

python manage.py runserver

## App Oluşturma

python manage.py startapp AppName

---------

Uygulama Oluşturduktan Sonra code içerisinde settings de AppName'i direk ekliyoruz.!

URL anadizin oluşturmak için App'in view'ı projenin URL'ine import edilir.
  from AppName import views
  path('', views.home)
