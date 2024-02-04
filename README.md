# Django-DB-Migration
Migration Django DBs can be a little hard, if the DB is quite big. This script is intended to have a smooth alternative to dump- &amp; load data and provides the ability to migrate Django-DBs with ease.
Note: This script was developed & tested for use with [DefectDojo](https://github.com/DefectDojo/django-DefectDojo), a Vulnerability Management System built upon Django. It may or may not work with other Django applications.

# Setup
This script just needs 3 small steps in order to migrate one django-db to another. It has been successfully tested with MySQL -> PostgreSQL but as it built upon Django logic it should run on other DB setups as well.

1. Setup a Second DB in your Django project
2. Add this script to your commands
3. Execute the script via 'python manage.py'
