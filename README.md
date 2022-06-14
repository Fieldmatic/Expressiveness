Expressiveness projekat


Za instalaciju potreban setuptools,venv ili virtualenv i Git bash na windows OS.

Instalacija projekta:
1. Napraviti novo virtuelno okruzenje i aktivirati ga
3. Uraditi pip install wheel, django, jinja2
4. Pozicionirati se u projekat terminalom
5. Pokrenuti skriptu run.sh (source run.sh na Unix OS) ili (run.sh na Windows OS)

Izvorisni plugini:
1. Plugin za parsiranje XML fajla u graf (source_xml folder)
2. Plugin za parsiranje JSON fajla u graf (data_json folder)

Plugini za vizuelizaciju:
1. Plugin za jednostavnu vizuelizaciju (visualisation_simple folder)
2. Plugin za kompleksnu vizuelzaciju (visualisation_complex folder)


Za rucnu instalaciju (Svi plugini se instaliraju pozicioniranjem u glavni folder komponente i komandom python setup.py install):
1. Instalirati prvo data_core plugin
2. Instalirati source_xml, data_json, visualisation_simple i visualisation_complex plugine
3. Pozicionirati se u django_project folder terminalom
4. Pokrenuti redom komande:
               python manage.py makemigrations data_core_app
               python manage.py migrate
               python manage.py runserver


