# Real-Time Emergency Health — Fall Detection (Django + JS)

Overview and setup instructions are included in the earlier assistant message. Run migrations and 'python manage.py runserver' to start.

Important notes and next steps:

I cannot directly place files on your local Desktop. Download the ZIP and extract it to your Desktop (or move it after downloading).

After extracting, from the project root run:

python -m venv .venv

activate the venv (source .venv/bin/activate on macOS/Linux or .venv\Scripts\Activate.ps1 on Windows PowerShell)

pip install -r requirements.txt

python manage.py makemigrations && python manage.py migrate

python manage.py createsuperuser (optional)

python manage.py runserver 0.0.0.0:8000 and open the site.
