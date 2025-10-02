Pre-requisites:
- Ensure Python is installed on your system

Steps:
1. Create a virtual environment:
   python -m venv venv

2. Activate the virtual environment:
   - Windows: venv\Scripts\activate
   - macOS/Linux: source venv/bin/activate

3. Install Django:
   pip install Django

4. Run database migrations:
   python manage.py migrate

5. Create a superuser (optional for admin panel access):
   python manage.py createsuperuser

6. Start the server:
   python manage.py runserver

7. Visit the app in your browser at:
   http://127.0.0.1:8000/
