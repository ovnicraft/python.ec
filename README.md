Python Ecuador Website
======================

Comunidad Python del Ecuador


Uso:

    pip install virtualenv
    virtualenv pyecenv
    source pyecenv/bin/activate
    pip install Django==1.4.5
    git clone https://github.com/PythonEcuador/python.ec.git pyec
    cd pyec
    pip install -r requirements.txt
    python manage.py syncdb
    python manage.py loaddata fixtures/*
    python manage.py runserver


Desarrolladores:
    
    Dairon Medina <daironm@kruger.com.ec>
    Cristian Salamea 
