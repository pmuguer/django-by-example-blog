# README

## Dependencias

django-haystack = "==2.8.0"
pysolr = "==3.3.2"

Tener en cuenta que hay un problema de compatibilidad entre Django 2.x
y solr; para que build\_solr\_schema funcione hay que aplicar el siguiente cambio:

https://github.com/django-haystack/django-haystack/pull/1504/commits/295584314e19a191a59450e053b21809adceca2a

