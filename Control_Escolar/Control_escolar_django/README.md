# Control escolar

Sistema de informaciónde de un control de estudio que consta de 4 modulos: Personal, Cursos, Inscripcion y Pruebas, ademas de integrar una agenda escolar.

Indicaciones  para levantar el sistema:


Instalar las herramientas neceasrias:
        pip -r requirements.txt

 Levantar el virtualenv:
        .\Scripts\activate

 Ubicarse dentro del directorio del proyecto a la altura del archivo manage.py y ejecutar los siguientes           comandos:

        4.1.- python manage.py makemigrations

        4.2.- python manage.py migrate

        4.3.- python manage.py createsuperuser

        4.4.- python manage.py runserver
