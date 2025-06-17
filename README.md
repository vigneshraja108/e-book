# e-book

## 🚀 How to Run This Django Project

```bash
git clone https://github.com/vigneshraja108/e-book.git
cd e-book
python -m venv venv
venv\Scripts\activate   # or source venv/bin/activate
cd ebook_store
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
