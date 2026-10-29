DJANGO PRODUCT MANAGEMENT PROJECT

1. Extract product_project.zip.
2. Open a terminal in the extracted product_project folder.
3. Install Django:
   python -m pip install django
4. Create the database tables:
   python manage.py makemigrations
   python manage.py migrate
5. Start the server:
   python manage.py runserver
6. Open:
   http://127.0.0.1:8000/

Features:
- Add products
- View all products
- Edit products
- Delete products

The database uses SQLite, which Django configures by default.
