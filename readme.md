# requirements
pip install -r requirements.txt

# Cheat sheet but in the name of all things holy go read the official documentation. 
##https://docs.djangoproject.com/en/3.1/
###django admin
python manage.py makemigrations [app]
python manage.py migrate
python manage.py runserver 

### remember to enable a filewatcher on the /static/bulma directory and run
sass bulma.sass ./css/style.css

####layouts
Some modification necessary. enable the examples app for details. 