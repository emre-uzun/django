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

>from AppName import views

>path('', views.home)

AppName views'da django.http in içindeki HttpResponse import edilir.

HTTP Response çalıştırılmıştır.

-------------

## Template Oluşturma

AppName altına gelinir ve sağ tıklayarak templates klasörü altına da AppName oluşturulur. 

AppName icine *.html uzantılı bir dosya oluşturulur ve views'den aşağıdaki gibi çağırılır.

> return render(request, "templates/AppName/xxxx.html")

