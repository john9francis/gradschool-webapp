Django structure:

Apps

Databases
- models = tables?

Views
- like a screen the user can see and interact with

three-step guide to making model changes:

* Change your models (in models.py).
* Run python manage.py makemigrations to create migrations for those changes
* Run python manage.py migrate to apply those changes to the database.

